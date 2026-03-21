# Binance (binance)
Binance is the world's largest cryptocurrency exchange by trading volume, offering a comprehensive suite of APIs for spot trading, derivatives, payments, and digital asset management. Their developer platform provides programmatic access to trading, wallet services, earning products, and merchant payment solutions across the Binance ecosystem.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/binance/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Cryptocurrency, Exchange, Trading, Blockchain, Digital Assets

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### Binance Spot Trading API
The Binance Spot Trading REST API provides programmatic access to the Binance spot exchange, the world's largest cryptocurrency trading platform by volume. Developers can place and manage orders, query account balances, retrieve real-time and historical market data, and manage trading pairs. The API supports limit, market, stop-loss, and other order types, along with account and trade history endpoints. Authentication uses HMAC SHA256 signed requests with API key and secret key credentials.

**Human URL:** [https://developers.binance.com/docs/binance-spot-api-docs/rest-api](https://developers.binance.com/docs/binance-spot-api-docs/rest-api)


#### Tags:

 - Cryptocurrency, Trading, Spot, Exchange, Market Data

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/rest-api)
- [OpenAPI](openapi/binance-spot-trading-openapi.yml)

### Binance Spot WebSocket API
The Binance Spot WebSocket API provides an alternative way to access spot trading functionality through persistent WebSocket connections. It is functionally equivalent to the REST API, accepting the same parameters and returning the same status and error codes, but offers lower latency for time-sensitive trading operations. Developers can place orders, cancel orders, and query account information over a single WebSocket connection without the overhead of establishing new HTTP connections for each request.

**Human URL:** [https://developers.binance.com/docs/binance-spot-api-docs/web-socket-api](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-api)


#### Tags:

 - Cryptocurrency, WebSocket, Streaming, Real-Time, Market Data

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-api)

### Binance Spot WebSocket Streams
Binance Spot WebSocket Streams deliver real-time market data updates via persistent WebSocket connections. Developers can subscribe to individual symbol ticker streams, aggregate trade streams, kline and candlestick data, depth-of-book updates, and mini-ticker streams. The service supports both single and combined stream subscriptions, enabling efficient consumption of live market data for trading bots, dashboards, and analytics applications without polling the REST API.

**Human URL:** [https://developers.binance.com/docs/binance-spot-api-docs/web-socket-streams](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-streams)


#### Tags:

 - Cryptocurrency, WebSocket, Streaming, Market Data, Real-Time

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/web-socket-streams)

### Binance USD-S Margined Futures API
The Binance USD-S Margined Futures API enables trading of USDT and BUSD margined perpetual and delivery futures contracts. Developers can place leveraged long and short positions, manage margin and leverage settings, query funding rates, and access futures-specific market data including mark price, index price, and open interest. The API supports advanced order types such as trailing stop and take-profit/stop-loss orders for sophisticated derivatives trading strategies.

**Human URL:** [https://developers.binance.com/docs/derivatives/usds-margined-futures/general-info](https://developers.binance.com/docs/derivatives/usds-margined-futures/general-info)


#### Tags:

 - Cryptocurrency, Futures, Derivatives, Trading, USDT

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/usds-margined-futures/general-info)
- [OpenAPI](openapi/binance-usds-margined-futures-openapi.yml)

### Binance COIN-M Futures API
The Binance COIN-M Futures API provides access to coin-margined perpetual and delivery futures contracts, where the margin and settlement currency is the base cryptocurrency rather than a stablecoin. This allows traders to use BTC, ETH, and other cryptocurrencies as collateral for leveraged positions. The API supports order placement, position management, margin adjustments, and market data retrieval for coin-margined derivatives products.

**Human URL:** [https://developers.binance.com/docs/derivatives/coin-margined-futures/general-info](https://developers.binance.com/docs/derivatives/coin-margined-futures/general-info)


#### Tags:

 - Cryptocurrency, Futures, Derivatives, Trading, Coin Margined

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/coin-margined-futures/general-info)
- [OpenAPI](openapi/binance-coin-margined-futures-openapi.yml)

### Binance European Options API
The Binance European Options API provides access to European-style cryptocurrency options contracts. Developers can trade call and put options on assets like BTC and ETH, query options chains with various strike prices and expiration dates, and retrieve options-specific market data including implied volatility and Greeks. The API enables programmatic options trading strategies such as hedging, income generation, and directional bets on cryptocurrency price movements.

**Human URL:** [https://developers.binance.com/docs/derivatives/option/general-info](https://developers.binance.com/docs/derivatives/option/general-info)


#### Tags:

 - Cryptocurrency, Options, Derivatives, Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/option/general-info)
- [OpenAPI](openapi/binance-european-options-openapi.yml)

### Binance Portfolio Margin API
The Binance Portfolio Margin API enables cross-margining across spot, futures, and options positions under a unified margin account. This risk-based margining system calculates margin requirements based on the overall portfolio risk rather than individual positions, allowing more capital-efficient trading. Developers can manage portfolio margin accounts, query unified account balances, and execute trades across multiple product types through a single API interface.

**Human URL:** [https://developers.binance.com/docs/derivatives/portfolio-margin/general-info](https://developers.binance.com/docs/derivatives/portfolio-margin/general-info)


#### Tags:

 - Cryptocurrency, Margin, Portfolio, Trading, Risk Management

#### Properties

- [Documentation](https://developers.binance.com/docs/derivatives/portfolio-margin/general-info)
- [OpenAPI](openapi/binance-portfolio-margin-openapi.yml)

### Binance Margin Trading API
The Binance Margin Trading API allows developers to programmatically access cross-margin and isolated-margin trading functionality. Users can borrow assets, place leveraged trades, repay loans, and manage margin account balances. The API provides endpoints for transferring assets between spot and margin accounts, querying interest rates and borrow limits, and monitoring margin level and liquidation thresholds for risk management purposes.

**Human URL:** [https://developers.binance.com/docs/margin_trading/general-info](https://developers.binance.com/docs/margin_trading/general-info)


#### Tags:

 - Cryptocurrency, Margin, Leverage, Trading, Borrowing

#### Properties

- [Documentation](https://developers.binance.com/docs/margin_trading/general-info)
- [OpenAPI](openapi/binance-margin-trading-openapi.yml)

### Binance Wallet API
The Binance Wallet API provides endpoints for managing cryptocurrency deposits, withdrawals, and account balances. Developers can query deposit and withdrawal history, retrieve deposit addresses, initiate withdrawals, check asset balances across all wallets, and access network and fee information for supported coins. The API also supports dust conversion, asset transfers between accounts, and querying system-wide asset details.

**Human URL:** [https://developers.binance.com/docs/wallet/introduction](https://developers.binance.com/docs/wallet/introduction)


#### Tags:

 - Cryptocurrency, Wallet, Deposits, Withdrawals, Account

#### Properties

- [Documentation](https://developers.binance.com/docs/wallet/introduction)
- [OpenAPI](openapi/binance-wallet-openapi.yml)

### Binance Sub-Account API
The Binance Sub-Account API enables institutional and enterprise users to manage multiple sub-accounts under a master account. Developers can create and manage sub-accounts, transfer assets between them, set trading permissions, query sub-account balances and transaction histories, and configure API keys for individual sub-accounts. This API is essential for fund managers, trading firms, and businesses that need to segregate assets and trading activity across multiple accounts.

**Human URL:** [https://developers.binance.com/docs/sub_account/general-info](https://developers.binance.com/docs/sub_account/general-info)


#### Tags:

 - Cryptocurrency, Sub-Account, Account Management, Enterprise

#### Properties

- [Documentation](https://developers.binance.com/docs/sub_account/general-info)
- [OpenAPI](openapi/binance-sub-account-openapi.yml)

### Binance Simple Earn API
The Binance Simple Earn API provides programmatic access to flexible and locked savings and staking products. Developers can subscribe to and redeem earn products, query available products and their interest rates, check subscription records and earned interest, and manage auto-subscribe settings. The API supports both flexible products that allow instant redemption and locked products that offer higher yields for fixed-term commitments.

**Human URL:** [https://developers.binance.com/docs/simple_earn/general-info](https://developers.binance.com/docs/simple_earn/general-info)


#### Tags:

 - Cryptocurrency, Earn, Staking, Yield, Savings

#### Properties

- [Documentation](https://developers.binance.com/docs/simple_earn/general-info)
- [OpenAPI](openapi/binance-simple-earn-openapi.yml)

### Binance Mining API
The Binance Mining API provides access to Binance Pool mining services. Developers can retrieve mining algorithms, available coins for mining, detailed miner statistics, earnings and revenue data, and hashrate resale information. The API enables mining operators and pools to programmatically monitor worker status, track mining profitability, and manage hashrate allocation across different mining algorithms and coins.

**Human URL:** [https://developers.binance.com/docs/mining/general-info](https://developers.binance.com/docs/mining/general-info)


#### Tags:

 - Cryptocurrency, Mining, Hash Rate, Pool

#### Properties

- [Documentation](https://developers.binance.com/docs/mining/general-info)

### Binance Copy Trading API
The Binance Copy Trading API allows developers to interact with the copy trading platform where users can automatically replicate the trades of experienced lead traders. The API provides endpoints for managing copy trading positions, querying lead trader portfolios and performance metrics, and configuring copy trading parameters such as investment amount and risk limits. It supports both futures copy trading for automated portfolio mirroring.

**Human URL:** [https://developers.binance.com/docs/copy_trading/general-info](https://developers.binance.com/docs/copy_trading/general-info)


#### Tags:

 - Cryptocurrency, Copy Trading, Social Trading, Trading

#### Properties

- [Documentation](https://developers.binance.com/docs/copy_trading/general-info)

### Binance Convert API
The Binance Convert API provides a simple interface for converting between cryptocurrencies and fiat currencies at quoted prices. Unlike order-book trading, the Convert API offers instant swaps with price quotes that are valid for a limited time window. Developers can request price quotes for asset pairs, accept quotes to execute conversions, and query conversion history. This API is well-suited for applications that need simple asset exchange without managing order books.

**Human URL:** [https://developers.binance.com/docs/convert/general-info](https://developers.binance.com/docs/convert/general-info)


#### Tags:

 - Cryptocurrency, Convert, Swap, Exchange

#### Properties

- [Documentation](https://developers.binance.com/docs/convert/general-info)

### Binance Pay API
The Binance Pay API enables merchants and businesses to accept cryptocurrency payments from Binance users. Developers can create payment orders, query payment status, process refunds, and manage merchant accounts. The API supports QR code payments, in-app payments, and online checkout flows for e-commerce integration. It also provides webhook notifications for real-time payment status updates and profit-sharing capabilities for platform businesses.

**Human URL:** [https://developers.binance.com/docs/binance-pay/introduction](https://developers.binance.com/docs/binance-pay/introduction)


#### Tags:

 - Cryptocurrency, Payments, Merchant, Commerce

#### Properties

- [Documentation](https://developers.binance.com/docs/binance-pay/introduction)
- [OpenAPI](openapi/binance-pay-openapi.yml)

### Binance Algo Trading API
The Binance Algo Trading API provides access to algorithmic order execution strategies such as TWAP (Time-Weighted Average Price) and volume participation algorithms. Developers can place large orders that are automatically broken into smaller child orders and executed over time to minimize market impact. The API supports creating, monitoring, and canceling algorithmic orders for both spot and futures markets, making it essential for institutional traders managing large position entries and exits.

**Human URL:** [https://developers.binance.com/docs/algo/general-info](https://developers.binance.com/docs/algo/general-info)


#### Tags:

 - Cryptocurrency, Algorithmic Trading, TWAP, VWAP

#### Properties

- [Documentation](https://developers.binance.com/docs/algo/general-info)

### Binance Auto-Invest API
The Binance Auto-Invest API enables developers to create and manage recurring cryptocurrency purchase plans, also known as dollar-cost averaging (DCA) strategies. Users can set up automated investment plans that periodically buy specified cryptocurrencies at regular intervals. The API provides endpoints for creating, modifying, and querying investment plans, viewing purchase history, and managing portfolio index-linked plans that automatically rebalance across multiple assets.

**Human URL:** [https://developers.binance.com/docs/auto_invest/general-info](https://developers.binance.com/docs/auto_invest/general-info)


#### Tags:

 - Cryptocurrency, Auto-Invest, DCA, Savings, Recurring

#### Properties

- [Documentation](https://developers.binance.com/docs/auto_invest/general-info)

### Binance Crypto Loan API
The Binance Crypto Loan API provides programmatic access to cryptocurrency-collateralized lending services. Developers can borrow assets by pledging cryptocurrency as collateral, repay outstanding loans, adjust collateral amounts, and query loan orders and repayment history. The API supports both flexible and fixed-term loan products with varying interest rates and loan-to-value ratios, enabling applications that need liquidity without selling underlying crypto holdings.

**Human URL:** [https://developers.binance.com/docs/crypto_loan/general-info](https://developers.binance.com/docs/crypto_loan/general-info)


#### Tags:

 - Cryptocurrency, Loans, Lending, Borrowing, Collateral

#### Properties

- [Documentation](https://developers.binance.com/docs/crypto_loan/general-info)

### Binance Gift Card API
The Binance Gift Card API allows developers to create, redeem, and verify cryptocurrency gift cards programmatically. Businesses can integrate gift card creation into rewards programs, promotional campaigns, and gifting platforms. The API supports creating gift cards with specific cryptocurrency denominations, verifying card validity, redeeming cards to user accounts, and querying creation and redemption history for reconciliation purposes.

**Human URL:** [https://developers.binance.com/docs/gift_card/general-info](https://developers.binance.com/docs/gift_card/general-info)


#### Tags:

 - Cryptocurrency, Gift Card, Voucher, Rewards

#### Properties

- [Documentation](https://developers.binance.com/docs/gift_card/general-info)

### Binance NFT API
The Binance NFT API provides endpoints for interacting with the Binance NFT marketplace programmatically. Developers can query NFT transaction history, deposit and withdrawal records, and asset information for non-fungible tokens held on the platform. The API supports retrieving NFT metadata, managing NFT deposits and withdrawals across supported blockchain networks, and accessing transaction history for tracking NFT portfolio activity.

**Human URL:** [https://developers.binance.com/docs/nft/general-info](https://developers.binance.com/docs/nft/general-info)


#### Tags:

 - Cryptocurrency, NFT, Digital Assets, Collectibles

#### Properties

- [Documentation](https://developers.binance.com/docs/nft/general-info)

### Binance Fiat API
The Binance Fiat API provides access to fiat currency deposit and withdrawal operations on the Binance platform. Developers can query fiat deposit and withdrawal order history, check available fiat payment methods, and retrieve transaction details for fiat-to-crypto and crypto-to-fiat conversions. The API supports multiple fiat currencies and payment channels, enabling applications that bridge traditional finance and cryptocurrency markets.

**Human URL:** [https://developers.binance.com/docs/fiat/general-info](https://developers.binance.com/docs/fiat/general-info)


#### Tags:

 - Cryptocurrency, Fiat, Deposits, Withdrawals, Currency

#### Properties

- [Documentation](https://developers.binance.com/docs/fiat/general-info)

## Common Properties

- [Developer Portal](https://developers.binance.com/)
- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/rest-api)
- [Website](https://www.binance.com/)
- [Blog](https://www.binance.com/en/blog)
- [Support](https://www.binance.com/en/support)
- [TermsOfService](https://www.binance.com/en/terms)
- [PrivacyPolicy](https://www.binance.com/en/privacy)
- [Login](https://accounts.binance.com/en/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
