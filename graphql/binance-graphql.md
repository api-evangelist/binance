# Binance GraphQL Schema

## Overview

This document describes a conceptual GraphQL schema for the Binance API surface. Binance exposes its functionality through REST and WebSocket APIs. This schema models the same domain objects and operations as a GraphQL layer, covering spot trading, margin trading, futures, wallet management, market data, and account operations.

**Provider:** Binance  
**Category:** Cryptocurrency Exchange  
**Base APIs:** REST (https://api.binance.com), WebSocket (wss://ws-api.binance.com)  
**Docs:** https://developers.binance.com/docs/binance-spot-api-docs/rest-api  
**Schema File:** binance-schema.graphql  

---

## Domain Coverage

### Account and Balances

The `Account` type is the root object representing a Binance user account. It aggregates balances across asset types including spot, margin, and futures wallets. `AssetBalance` holds the free and locked quantities for a single asset. `MarginBalance` extends this with borrowed and interest amounts for cross-margin accounts. `FuturesBalance` captures wallet balance and unrealized profit/loss for USD-M or COIN-M futures accounts.

### Orders

`SpotOrder` represents a limit, market, stop-loss, or other order placed on the spot exchange. `MarginOrder` is the equivalent for cross-margin or isolated-margin trading. `FuturesOrder` covers orders on perpetual or delivery futures contracts. `OCOOrder` (One-Cancels-the-Other) groups two orders where filling one cancels the other. `OrderFill` records individual fill events within an order, including price, quantity, and commission. `CancelResponse` captures the server acknowledgment when an order is cancelled.

### Trades

`Trade` represents an executed match between a buyer and seller. It includes the price, quantity, and timestamp. `AggTrade` is an aggregated trade that compresses multiple trades executed at the same price and time into a single record, used for efficient market data delivery.

### Market Data

`Symbol` identifies a trading pair (e.g., BTCUSDT). `SymbolInfo` carries full metadata about a symbol including base and quote asset, status, and applicable filters. `SymbolFilter` encodes the trading rules for a symbol such as minimum lot size, price precision, and notional value limits. `OrderBook` holds the current bids and asks for a symbol. `Depth` is a snapshot or update of order book depth. `OrderBookEntry` is a single price level with its quantity. `Ticker` is the 24-hour rolling statistics for a symbol including price change, high, low, and volume. `MiniTicker` is a compact version with fewer fields. `BookTicker` is the best bid and ask price and quantity.

### Candlestick and OHLCV Data

`KlineData` is a candlestick record keyed by interval (1m, 5m, 1h, etc.). `OHLCV` holds the open, high, low, close, and volume for a time period. `MarketTrend` describes directional movement and momentum. `MarketSummary` aggregates exchange-wide statistics.

### Coins and Networks

`CoinInfo` describes a cryptocurrency including its full name, networks it is available on, and trading status. `NetworkInfo` describes a blockchain network including withdrawal fees, confirmation requirements, and deposit/withdrawal availability.

### Wallet Operations

`DepositAddress` is a generated address for depositing a specific coin on a specific network. `WithdrawalRecord` captures a completed or pending withdrawal including status, transaction hash, and fee. `DepositRecord` captures a completed or pending deposit.

### Funding and Positions

`Funding` represents a funding payment in futures. `FundingFee` is the fee charged or credited at each funding interval. `Position` describes an open futures position including size, entry price, and unrealized PnL. `PositionRisk` adds margin ratio, liquidation price, and maintenance margin. `MarkPrice` is the index-smoothed price used to calculate funding and liquidation. `Liquidation` records a forced liquidation event. `IndexPrice` is the spot index price underpinning a futures contract.

### Streaming and User Data

`UserDataStream` is the session object for a private WebSocket stream. `ListenKey` is the authentication token that authorizes the private stream connection.

### Exchange Metadata

`ExchangeInfo` is the top-level exchange configuration returned from /api/v3/exchangeInfo, containing symbols, rate limits, and server time. `SystemStatus` indicates whether the exchange and its APIs are operational. `ServerTime` is the exchange's current Unix millisecond timestamp. `RateLimits` captures the request weight and order count limits.

### Enumerations

`OrderType` enumerates LIMIT, MARKET, STOP_LOSS, STOP_LOSS_LIMIT, TAKE_PROFIT, TAKE_PROFIT_LIMIT, and LIMIT_MAKER. `TimeInForce` enumerates GTC (Good Till Cancel), IOC (Immediate or Cancel), FOK (Fill or Kill), and GTX. `Side` is BUY or SELL. `OrderStatus` enumerates NEW, PARTIALLY_FILLED, FILLED, CANCELED, PENDING_CANCEL, REJECTED, and EXPIRED. `ExecutionType` enumerates NEW, CANCELED, REPLACED, REJECTED, TRADE, and EXPIRED. `Permission` enumerates SPOT, MARGIN, LEVERAGED, and TRD_GRP access modes.

### Margin-Specific Types

`CrossMarginOrder` is an order placed using cross-margin collateral. `IsolatedMarginOrder` is an order placed against a single symbol's isolated margin pool. `MarginLoan` records a borrow event including asset, amount, timestamp, and repayment status. `MarginRepay` records a repayment event.

### Earn and Staking

`FlexibleProduct` describes a simple earn flexible savings product including estimated APR and subscription limits. `StakingProduct` describes a locked staking product with fixed term and yield.

### Portfolio Margin

`PortfolioMargin` represents the unified cross-margined account state used in Binance's portfolio margin mode, covering unified margin balance and cross-product risk offsets.

---

## Query Structure

The schema exposes a `Query` root type with fields covering:

- `account`: Authenticated account details and wallet balances
- `spotOrder` / `spotOrders`: Single and list order queries
- `openOrders`: All active orders for an account or symbol
- `orderBook`: Current depth for a symbol
- `ticker` / `tickers`: 24h statistics for one or all symbols
- `klines`: Candlestick data for a symbol and interval
- `exchangeInfo`: Full exchange configuration
- `systemStatus`: Exchange operational status
- `serverTime`: Current server timestamp
- `coinInfo`: Metadata for a specific coin
- `depositAddress`: Generated deposit address for a coin/network
- `depositHistory`: Paginated list of past deposits
- `withdrawalHistory`: Paginated list of past withdrawals
- `position` / `positions`: Open futures positions
- `markPrice`: Current mark price for a futures symbol
- `fundingRate`: Current and historical funding rates
- `marginAccount`: Cross-margin or isolated-margin account data

## Mutation Structure

The schema exposes a `Mutation` root type with fields covering:

- `placeSpotOrder`: Submit a new spot order
- `cancelSpotOrder`: Cancel an existing spot order
- `placeOCOOrder`: Submit an OCO order pair
- `placeFuturesOrder`: Submit a new futures order
- `cancelFuturesOrder`: Cancel a futures order
- `createListenKey`: Create a user data stream listen key
- `keepAliveListenKey`: Renew a listen key before it expires
- `closeListenKey`: Close a user data stream
- `withdraw`: Initiate a cryptocurrency withdrawal
- `borrowMargin`: Borrow assets for margin trading
- `repayMargin`: Repay borrowed margin assets
- `transferAsset`: Transfer assets between spot and margin wallets

## Subscription Structure

The schema exposes a `Subscription` root type for real-time streams:

- `orderBookUpdate`: Incremental depth updates for a symbol
- `tickerUpdate`: Real-time 24h ticker data
- `tradeStream`: Live trade events
- `aggTradeStream`: Aggregated trade events
- `klineStream`: Real-time candlestick updates
- `userDataStream`: Private account order and balance updates

---

## Schema File

See `binance-schema.graphql` for the full type definitions.
