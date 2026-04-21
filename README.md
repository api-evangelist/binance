# Binance (binance)
Binance is the world's largest cryptocurrency exchange by trading volume, providing APIs for spot trading, futures, margin, wallet management, and market data across 19+ specialized REST APIs and WebSocket streams.

**URL:** [https://developers.binance.com/](https://developers.binance.com/)

## Tags:

 - Cryptocurrency, Exchange, Trading, Blockchain, Finance, DeFi, Market Data

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

Binance exposes 19+ specialized REST APIs including:

- **Spot Trading** — Place and manage spot orders across 500+ pairs
- **USD-M Futures** — Perpetual and delivery futures settled in USDT
- **Coin-M Futures** — Futures settled in cryptocurrency
- **Margin Trading** — Cross and isolated margin trading
- **Wallet** — Deposits, withdrawals, and transfers
- **Simple Earn** — Flexible and locked earning products
- **Convert** — Instant cryptocurrency conversion
- **NFT** — NFT marketplace API
- **Pay** — Binance Pay merchant API
- **Sub-Account** — Sub-account management
- **Algo Trading** — TWAP and VP algorithmic orders

## Common Properties

- [Portal](https://developers.binance.com/)
- [Documentation](https://developers.binance.com/docs/binance-spot-api-docs/)
- [GettingStarted](https://developers.binance.com/docs/binance-spot-api-docs/rest-api)
- [GitHubOrganization](https://github.com/binance)

## Features

| Name | Description |
|------|-------------|
| Spot Trading | Buy and sell 500+ cryptocurrency pairs with limit, market, and stop-loss orders. |
| USD-M Futures | Trade perpetual and delivery futures contracts settled in USDT. |
| Coin-M Futures | Trade perpetual and delivery futures contracts settled in cryptocurrency. |
| Margin Trading | Trade on margin with up to 10x leverage using borrowed assets. |
| Algo Trading | Place algorithmic orders using TWAP, VP, and other execution strategies. |
| WebSocket Streams | Real-time market data streams for price, depth, and trade updates. |
| Wallet Management | Manage deposits, withdrawals, and asset transfers between wallets. |
| Simple Earn | Earn interest on idle cryptocurrency assets through flexible and locked products. |

## Use Cases

| Name | Description |
|------|-------------|
| Algorithmic Trading | Build automated trading bots using Binance REST and WebSocket APIs. |
| Portfolio Management | Track and rebalance cryptocurrency portfolios programmatically. |
| Market Data Aggregation | Aggregate real-time price and order book data for analysis or display. |
| DeFi Integration | Bridge centralized Binance liquidity into DeFi protocols. |
| Arbitrage Trading | Exploit price differences across Binance spot, futures, and margin markets. |

## Integrations

| Name | Description |
|------|-------------|
| TradingView | Connect Binance to TradingView for charting and automated alert-based trading. |
| MetaTrader | Use MetaTrader bridge adapters to trade Binance from MT4/MT5. |
| Telegram | Receive Binance trade notifications and alerts via Telegram bot. |
| AWS Lambda | Run serverless trading bots triggered by events on AWS Lambda. |
| Python CCXT | Access Binance through the CCXT unified cryptocurrency exchange library. |

## Artifacts

### OpenAPI

- [Binance Spot Trading API](openapi/binance-spot-trading-openapi.yml)
- [Binance USD-M Futures API](openapi/binance-usds-margined-futures-openapi.yml)
- [Binance Margin Trading API](openapi/binance-margin-trading-openapi.yml)
- [Binance Wallet API](openapi/binance-wallet-openapi.yml)
- And 15 more in openapi/

### JSON Schema

- [binance-order-schema.json](json-schema/binance-order-schema.json)
- [binance-account-schema.json](json-schema/binance-account-schema.json)
- [binance-trade-schema.json](json-schema/binance-trade-schema.json)

## Capabilities

### Shared Per-API Definitions

- [Binance Spot Trading API](capabilities/shared/binance.yaml) — 9 operations for market data, trading, and account management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Spot Trading](capabilities/spot-trading.yaml) | Binance | 9 | Trader, Quant Developer |

## Vocabulary

- [Binance Vocabulary](vocabulary/binance-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 4 actions, 1 workflow, and 2 personas

## Rules

- [Binance Spectral Rules](rules/binance-spectral-rules.yml) — 24 rules across 9 categories enforcing Binance API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
