# FI Trading Platform
### IBKR-Integrated Trading Operations, Execution & Portfolio Analytics

A Django-based trading platform designed to support trading operations through Interactive Brokers (IBKR), combining live market data, Level 2 market depth, order management, position monitoring, portfolio analytics, and operational visibility in a unified dashboard.

This public repository provides a **sanitized technical overview, demonstration video, and platform documentation**. The underlying implementation is proprietary and is not included.

## Project Overview

The FI Trading Platform brings together trading operations and portfolio monitoring workflows in a single web-based interface. It integrates with IBKR to support market-data visibility, manual order execution, order monitoring, account-level performance tracking, and configurable algorithm controls.

The platform was designed around practical trading-system requirements: accessing market information, managing order workflows, monitoring positions and P&L, and providing operational visibility to users.

## Key Capabilities

### 1. Live Market Data & Market Depth
- Integration with Interactive Brokers for live market-data access.
- Level 2 order-book visualization with up to 20 levels on each side, as documented.
- Market reference information, including day high, day low, and previous US-session close.
- Live charts and trading-session volume analysis.

### 2. Order Management & Execution
- Manual market and limit order workflows.
- Support for Good-Till-Cancelled (GTC) and Good-Till-Date (GTD) order instructions.
- Configurable regular-trading-hours and time-related order controls.
- Saved-order workflows and management of open orders.
- Order activity and trade monitoring.

### 3. Algorithm Controls & Risk Parameters
- Algo Controller interface for configuring trading controls.
- Maximum-order-quantity protection.
- Configurable entry and exit slippage parameters.

These controls provide configurable safeguards and operational parameters. Their presence should not be interpreted as a claim that the platform guarantees execution quality or eliminates trading risk.

### 4. Positions, P&L & Portfolio Analytics
- Live position and account information through IBKR integration.
- Daily, realized, unrealized, month-to-date (MTD), and year-to-date (YTD) P&L views, as documented.
- Portfolio heatmaps and cumulative mark-to-market (MTM) visualizations.
- Strategy-level performance analytics.

### 5. Alerts & Operational Monitoring
- Price alerts with SMTP-based notifications.
- Activity logs and trade records.
- Error visibility and operational monitoring.
- Role-based access for Super Admin, Admin, and Portfolio Manager users.

## Technology Stack

The documented platform uses:

- **Language:** Python
- **Web framework:** Django
- **Broker integration:** Interactive Brokers (IBKR)
- **Frontend:** Web-based trading dashboard
- **Trading functionality:** Market data, Level 2 depth, order workflows, positions, P&L, and portfolio analytics

The repository intentionally does not disclose proprietary implementation details, internal infrastructure, credentials, or confidential configuration.

## Architecture & Workflow

At a conceptual level, the platform connects broker-provided market and account information to a web-based interface for trading operations and portfolio monitoring.

The main functional areas are:

1. **Broker connectivity:** Access market and account information through IBKR.
2. **Market-data presentation:** Display market prices, market depth, charts, and session statistics.
3. **Trading operations:** Provide interfaces for manual order entry and open-order management.
4. **Algorithm controls:** Expose configurable order-quantity and slippage parameters.
5. **Portfolio monitoring:** Present positions, P&L, and portfolio analytics.
6. **Operational visibility:** Provide activity logs, trade records, alerts, and error information.

This is a functional overview, not a disclosure of the complete internal architecture or implementation.

## Demonstration & Documentation

The public repository includes the following materials:

- **`dashboard_demo.mp4`** — Demonstration of the platform's user interface and documented workflows.
- **`FI_Trading_Platform_Documentation.pdf`** — Technical documentation describing platform capabilities, dashboard modules, and representative workflows.

These materials are intended to help recruiters and engineering reviewers understand the system's scope without access to its proprietary source code.

## Engineering Scope

The platform demonstrates experience with the integration of broker-connected trading workflows and web-based operational tooling, including:

- Market-data and Level 2 visualization.
- Order-entry and open-order management interfaces.
- Position and account-level P&L monitoring.
- Configurable trading controls.
- Portfolio and strategy analytics.
- Operational logging, alerts, and error visibility.

For technical discussions, the emphasis is on system functionality, integration requirements, trading workflows, design considerations, and the engineering responsibilities undertaken during development.

## Source Code & Confidentiality

This repository is a **sanitized portfolio presentation**, not an open-source release.

The production implementation and source code are proprietary and therefore are not published here. The demonstration video and technical documentation have been provided to communicate the platform's capabilities while respecting confidentiality restrictions.

No credentials, private account information, or confidential production configuration are intentionally included in this public repository.

## Intended Audience

This project is relevant to engineering roles involving:

- Trading Systems Engineering
- Quantitative Development
- Market Data Engineering
- Algorithmic Trading Infrastructure
- Financial Technology and Trading Applications

The project illustrates trading-platform functionality and integration work. It is not presented as an independently validated quantitative alpha strategy, a public backtesting framework, or a benchmarked low-latency execution engine.

---

**Project type:** Proprietary trading platform  
**Public artifacts:** Demonstration video and sanitized technical documentation  
**Source code:** Not publicly available  
**Broker integration:** Interactive Brokers (IBKR)
