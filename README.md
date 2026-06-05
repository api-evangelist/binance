# Binance (binance)

Binance is the world's largest cryptocurrency exchange by trading volume, providing APIs for spot trading, futures, margin, wallet management, and market data across 19+ specialized REST APIs and WebSocket streams.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Cryptocurrency
- Exchange
- Trading
- Blockchain
- Finance
- DeFi
- Market Data

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Binance Spot Trading API

The Binance Spot Trading REST API provides programmatic access to the Binance spot exchange, the world's largest cryptocurrency trading platform by volume. Developers can place and manage orders, query account balances, retrieve real-time and historical market data, and manage trading pairs. The API supports limit, market, stop-loss, and other order types, along with account and trade history endpoints. Authentication uses HMAC SHA256 signed requests with API key and secret key credentials.

- **Human URL:** [https://developers.binance.com/docs/binance-spot-api-docs/rest-api](https://developers.binance.com/docs/binance-spot-api-docs/rest-api)
- **Base URL:** `https://api.binance.com`

#### Tags

- Cryptocurrency
- Exchange
- Market Data
- Spot
- Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/rest-api)
- [OpenAPI](openapi/binance-spot-trading-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-spot-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-spot-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Spot WebSocket API

The Binance Spot WebSocket API provides an alternative way to access spot trading functionality through persistent WebSocket connections. It is functionally equivalent to the REST API, accepting the same parameters and returning the same status and error codes, but offers lower latency for time-sensitive trading operations.

- **Human URL:** [https://developers.binance.com/docs/binance-spot-api-docs/web-socket-api](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-api)
- **Base URL:** `wss://ws-api.binance.com`

#### Tags

- Cryptocurrency
- Market Data
- Real-Time
- Streaming
- WebSocket

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-api)
- [AsyncAPI](asyncapi/binance-spot-websocket-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/binance-algo-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-algo-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-auto-invest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-auto-invest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-coin-margined-futures.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-coin-margined-futures.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-convert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-convert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-copy-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-copy-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-crypto-loan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-crypto-loan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-european-options.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-european-options.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-fiat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-fiat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-gift-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-gift-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-mining.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-mining.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-nft.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-nft.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-portfolio-margin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-portfolio-margin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-simple-earn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-simple-earn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-spot-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-spot-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-sub-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-sub-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-usds-margined-futures.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-usds-margined-futures.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-wallet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-wallet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Spot WebSocket Streams

Binance Spot WebSocket Streams deliver real-time market data updates via persistent WebSocket connections. Developers can subscribe to individual symbol ticker streams, aggregate trade streams, kline and candlestick data, depth-of-book updates, and mini-ticker streams. The service supports both single and combined stream subscriptions, enabling efficient consumption of live market data for trading bots, dashboards, and analytics applications without polling the REST API.

- **Human URL:** [https://developers.binance.com/docs/binance-spot-api-docs/web-socket-streams](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-streams)
- **Base URL:** `wss://stream.binance.com`

#### Tags

- Cryptocurrency
- Market Data
- Real-Time
- Streaming
- WebSocket

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-streams)
- [AsyncAPI](asyncapi/binance-spot-websocket-streams-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/binance-algo-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-algo-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-auto-invest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-auto-invest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-coin-margined-futures.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-coin-margined-futures.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-convert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-convert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-copy-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-copy-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-crypto-loan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-crypto-loan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-european-options.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-european-options.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-fiat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-fiat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-gift-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-gift-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-mining.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-mining.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-nft.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-nft.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-portfolio-margin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-portfolio-margin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-simple-earn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-simple-earn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-spot-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-spot-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-sub-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-sub-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-usds-margined-futures.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-usds-margined-futures.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/binance-wallet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-wallet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance USD-S Margined Futures API

The Binance USD-S Margined Futures API enables trading of USDT and BUSD margined perpetual and delivery futures contracts. Developers can place leveraged long and short positions, manage margin and leverage settings, query funding rates, and access futures-specific market data including mark price, index price, and open interest. The API supports advanced order types such as trailing stop and take-profit/stop-loss orders for sophisticated derivatives trading strategies.

- **Human URL:** [https://developers.binance.com/docs/derivatives/usds-margined-futures/general-info](https://developers.binance.com/docs/derivatives/usds-margined-futures/general-info)
- **Base URL:** `https://fapi.binance.com`

#### Tags

- Cryptocurrency
- Derivatives
- Futures
- Trading
- USDT

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/usds-margined-futures/general-info)
- [OpenAPI](openapi/binance-usds-margined-futures-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-usds-margined-futures.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-usds-margined-futures.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance COIN-M Futures API

The Binance COIN-M Futures API provides access to coin-margined perpetual and delivery futures contracts, where the margin and settlement currency is the base cryptocurrency rather than a stablecoin. This allows traders to use BTC, ETH, and other cryptocurrencies as collateral for leveraged positions. The API supports order placement, position management, margin adjustments, and market data retrieval for coin-margined derivatives products.

- **Human URL:** [https://developers.binance.com/docs/derivatives/coin-margined-futures/general-info](https://developers.binance.com/docs/derivatives/coin-margined-futures/general-info)
- **Base URL:** `https://dapi.binance.com`

#### Tags

- Coin Margined
- Cryptocurrency
- Derivatives
- Futures
- Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/coin-margined-futures/general-info)
- [OpenAPI](openapi/binance-coin-margined-futures-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-coin-margined-futures.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-coin-margined-futures.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance European Options API

The Binance European Options API provides access to European-style cryptocurrency options contracts. Developers can trade call and put options on assets like BTC and ETH, query options chains with various strike prices and expiration dates, and retrieve options-specific market data including implied volatility and Greeks. The API enables programmatic options trading strategies such as hedging, income generation, and directional bets on cryptocurrency price movements.

- **Human URL:** [https://developers.binance.com/docs/derivatives/option/general-info](https://developers.binance.com/docs/derivatives/option/general-info)
- **Base URL:** `https://eapi.binance.com`

#### Tags

- Cryptocurrency
- Derivatives
- Options
- Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/option/general-info)
- [OpenAPI](openapi/binance-european-options-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-european-options.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-european-options.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Portfolio Margin API

The Binance Portfolio Margin API enables cross-margining across spot, futures, and options positions under a unified margin account. This risk-based margining system calculates margin requirements based on the overall portfolio risk rather than individual positions, allowing more capital-efficient trading. Developers can manage portfolio margin accounts, query unified account balances, and execute trades across multiple product types through a single API interface.

- **Human URL:** [https://developers.binance.com/docs/derivatives/portfolio-margin/general-info](https://developers.binance.com/docs/derivatives/portfolio-margin/general-info)
- **Base URL:** `https://papi.binance.com`

#### Tags

- Cryptocurrency
- Margin
- Portfolio
- Risk Management
- Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/portfolio-margin/general-info)
- [OpenAPI](openapi/binance-portfolio-margin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-portfolio-margin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-portfolio-margin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Margin Trading API

The Binance Margin Trading API allows developers to programmatically access cross-margin and isolated-margin trading functionality. Users can borrow assets, place leveraged trades, repay loans, and manage margin account balances. The API provides endpoints for transferring assets between spot and margin accounts, querying interest rates and borrow limits, and monitoring margin level and liquidation thresholds for risk management purposes.

- **Human URL:** [https://developers.binance.com/docs/margin_trading/general-info](https://developers.binance.com/docs/margin_trading/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Borrowing
- Cryptocurrency
- Leverage
- Margin
- Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/margin_trading/general-info)
- [OpenAPI](openapi/binance-margin-trading-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Binance Wallet API

The Binance Wallet API provides endpoints for managing cryptocurrency deposits, withdrawals, and account balances. Developers can query deposit and withdrawal history, retrieve deposit addresses, initiate withdrawals, check asset balances across all wallets, and access network and fee information for supported coins. The API also supports dust conversion, asset transfers between accounts, and querying system-wide asset details.

- **Human URL:** [https://developers.binance.com/docs/wallet/introduction](https://developers.binance.com/docs/wallet/introduction)
- **Base URL:** `https://api.binance.com`

#### Tags

- Account
- Cryptocurrency
- Deposits
- Wallet
- Withdrawals

#### Properties

- [Documentation](https://developers.binance.com/docs/wallet/introduction)
- [OpenAPI](openapi/binance-wallet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-wallet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-wallet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Sub-Account API

The Binance Sub-Account API enables institutional and enterprise users to manage multiple sub-accounts under a master account. Developers can create and manage sub-accounts, transfer assets between them, set trading permissions, query sub-account balances and transaction histories, and configure API keys for individual sub-accounts. This API is essential for fund managers, trading firms, and businesses that need to segregate assets and trading activity across multiple accounts.

- **Human URL:** [https://developers.binance.com/docs/sub_account/general-info](https://developers.binance.com/docs/sub_account/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Account Management
- Cryptocurrency
- Enterprise
- Sub-Account

#### Properties

- [Documentation](https://developers.binance.com/docs/sub_account/general-info)
- [OpenAPI](openapi/binance-sub-account-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-sub-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-sub-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Simple Earn API

The Binance Simple Earn API provides programmatic access to flexible and locked savings and staking products. Developers can subscribe to and redeem earn products, query available products and their interest rates, check subscription records and earned interest, and manage auto-subscribe settings. The API supports both flexible products that allow instant redemption and locked products that offer higher yields for fixed-term commitments.

- **Human URL:** [https://developers.binance.com/docs/simple_earn/general-info](https://developers.binance.com/docs/simple_earn/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Cryptocurrency
- Earn
- Savings
- Staking
- Yield

#### Properties

- [Documentation](https://developers.binance.com/docs/simple_earn/general-info)
- [OpenAPI](openapi/binance-simple-earn-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-simple-earn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-simple-earn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Mining API

The Binance Mining API provides access to Binance Pool mining services. Developers can retrieve mining algorithms, available coins for mining, detailed miner statistics, earnings and revenue data, and hashrate resale information. The API enables mining operators and pools to programmatically monitor worker status, track mining profitability, and manage hashrate allocation across different mining algorithms and coins.

- **Human URL:** [https://developers.binance.com/docs/mining/general-info](https://developers.binance.com/docs/mining/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Cryptocurrency
- Hash Rate
- Mining
- Pool

#### Properties

- [Documentation](https://developers.binance.com/docs/mining/general-info)
- [OpenAPI](openapi/binance-mining-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-mining.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-mining.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Copy Trading API

The Binance Copy Trading API allows developers to interact with the copy trading platform where users can automatically replicate the trades of experienced lead traders. The API provides endpoints for managing copy trading positions, querying lead trader portfolios and performance metrics, and configuring copy trading parameters such as investment amount and risk limits. It supports both futures copy trading for automated portfolio mirroring.

- **Human URL:** [https://developers.binance.com/docs/copy_trading/general-info](https://developers.binance.com/docs/copy_trading/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Copy Trading
- Cryptocurrency
- Social Trading
- Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/copy_trading/general-info)
- [OpenAPI](openapi/binance-copy-trading-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-copy-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-copy-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Convert API

The Binance Convert API provides a simple interface for converting between cryptocurrencies and fiat currencies at quoted prices. Unlike order-book trading, the Convert API offers instant swaps with price quotes that are valid for a limited time window. Developers can request price quotes for asset pairs, accept quotes to execute conversions, and query conversion history. This API is well-suited for applications that need simple asset exchange without managing order books.

- **Human URL:** [https://developers.binance.com/docs/convert/general-info](https://developers.binance.com/docs/convert/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Convert
- Cryptocurrency
- Exchange
- Swap

#### Properties

- [Documentation](https://developers.binance.com/docs/convert/general-info)
- [OpenAPI](openapi/binance-convert-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-convert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-convert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Pay API

The Binance Pay API enables merchants and businesses to accept cryptocurrency payments from Binance users. Developers can create payment orders, query payment status, process refunds, and manage merchant accounts. The API supports QR code payments, in-app payments, and online checkout flows for e-commerce integration. It also provides webhook notifications for real-time payment status updates and profit-sharing capabilities for platform businesses.

- **Human URL:** [https://developers.binance.com/docs/binance-pay/introduction](https://developers.binance.com/docs/binance-pay/introduction)
- **Base URL:** `https://bpay.binanceapi.com`

#### Tags

- Commerce
- Cryptocurrency
- Merchant
- Payments

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-pay/introduction)
- [OpenAPI](openapi/binance-pay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-pay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-pay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/binance-pay-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Binance Algo Trading API

The Binance Algo Trading API provides access to algorithmic order execution strategies such as TWAP (Time-Weighted Average Price) and volume participation algorithms. Developers can place large orders that are automatically broken into smaller child orders and executed over time to minimize market impact.

- **Human URL:** [https://developers.binance.com/docs/algo/general-info](https://developers.binance.com/docs/algo/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Algorithmic Trading
- Cryptocurrency
- TWAP
- VWAP

#### Properties

- [Documentation](https://developers.binance.com/docs/algo/general-info)
- [OpenAPI](openapi/binance-algo-trading-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-algo-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-algo-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Auto-Invest API

The Binance Auto-Invest API enables developers to create and manage recurring cryptocurrency purchase plans, also known as dollar-cost averaging (DCA) strategies. Users can set up automated investment plans that periodically buy specified cryptocurrencies at regular intervals. The API provides endpoints for creating, modifying, and querying investment plans, viewing purchase history, and managing portfolio index-linked plans that automatically rebalance across multiple assets.

- **Human URL:** [https://developers.binance.com/docs/auto_invest/general-info](https://developers.binance.com/docs/auto_invest/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Auto-Invest
- Cryptocurrency
- DCA
- Recurring
- Savings

#### Properties

- [Documentation](https://developers.binance.com/docs/auto_invest/general-info)
- [OpenAPI](openapi/binance-auto-invest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-auto-invest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-auto-invest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Crypto Loan API

The Binance Crypto Loan API provides programmatic access to cryptocurrency-collateralized lending services. Developers can borrow assets by pledging cryptocurrency as collateral, repay outstanding loans, adjust collateral amounts, and query loan orders and repayment history. The API supports both flexible and fixed-term loan products with varying interest rates and loan-to-value ratios, enabling applications that need liquidity without selling underlying crypto holdings.

- **Human URL:** [https://developers.binance.com/docs/crypto_loan/general-info](https://developers.binance.com/docs/crypto_loan/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Borrowing
- Collateral
- Cryptocurrency
- Lending
- Loans

#### Properties

- [Documentation](https://developers.binance.com/docs/crypto_loan/general-info)
- [OpenAPI](openapi/binance-crypto-loan-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-crypto-loan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-crypto-loan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Gift Card API

The Binance Gift Card API allows developers to create, redeem, and verify cryptocurrency gift cards programmatically. Businesses can integrate gift card creation into rewards programs, promotional campaigns, and gifting platforms. The API supports creating gift cards with specific cryptocurrency denominations, verifying card validity, redeeming cards to user accounts, and querying creation and redemption history for reconciliation purposes.

- **Human URL:** [https://developers.binance.com/docs/gift_card/general-info](https://developers.binance.com/docs/gift_card/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Cryptocurrency
- Gift Card
- Rewards
- Voucher

#### Properties

- [Documentation](https://developers.binance.com/docs/gift_card/general-info)
- [OpenAPI](openapi/binance-gift-card-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-gift-card.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-gift-card.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance NFT API

The Binance NFT API provides endpoints for interacting with the Binance NFT marketplace programmatically. Developers can query NFT transaction history, deposit and withdrawal records, and asset information for non-fungible tokens held on the platform. The API supports retrieving NFT metadata, managing NFT deposits and withdrawals across supported blockchain networks, and accessing transaction history for tracking NFT portfolio activity.

- **Human URL:** [https://developers.binance.com/docs/nft/general-info](https://developers.binance.com/docs/nft/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Collectibles
- Cryptocurrency
- Digital Assets
- NFT

#### Properties

- [Documentation](https://developers.binance.com/docs/nft/general-info)
- [OpenAPI](openapi/binance-nft-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-nft.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-nft.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Binance Fiat API

The Binance Fiat API provides access to fiat currency deposit and withdrawal operations on the Binance platform. Developers can query fiat deposit and withdrawal order history, check available fiat payment methods, and retrieve transaction details for fiat-to-crypto and crypto-to-fiat conversions. The API supports multiple fiat currencies and payment channels, enabling applications that bridge traditional finance and cryptocurrency markets.

- **Human URL:** [https://developers.binance.com/docs/fiat/general-info](https://developers.binance.com/docs/fiat/general-info)
- **Base URL:** `https://api.binance.com`

#### Tags

- Cryptocurrency
- Currency
- Deposits
- Fiat
- Withdrawals

#### Properties

- [Documentation](https://developers.binance.com/docs/fiat/general-info)
- [OpenAPI](openapi/binance-fiat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binance-fiat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binance-fiat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/binance)
- [Portal](https://developers.binance.com/)
- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/)
- [Getting Started](https://developers.binance.com/docs/binance-spot-api-docs/rest-api)
- [GitHub Organization](https://github.com/binance)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/rules/binance-spectral-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/vocabulary/binance-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Agent Skill](https://github.com/binance/binance-skills-hub)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
