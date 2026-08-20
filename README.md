# Awesome Wealth Management [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source Python, Go, and Rust libraries and packages for wealth management, asset management, and estate planning.

This list catalogs actively-maintained, open-source tooling relevant to building software for portfolio management, risk analytics, market data access, quantitative finance, accounting, tax, actuarial/estate planning, compliance, and backtesting — across three languages: **Python**, **Go**, and **Rust**.

Some categories (Tax, Estate Planning, Compliance) have few or no credible entries in Go and Rust today; those language rows are simply omitted rather than padded with off-topic or unmaintained packages. See [Contributing](#contributing) if you know of one that belongs here.

Star counts are pulled live from GitHub via [shields.io](https://shields.io) badges, so they stay current without manual updates to this file.

## Contents

- [Portfolio & Asset Management](#portfolio--asset-management)
- [Risk & Performance Analytics](#risk--performance-analytics)
- [Financial Data & Market Access](#financial-data--market-access)
- [Quantitative Finance & Derivatives Pricing](#quantitative-finance--derivatives-pricing)
- [Accounting & Ledger](#accounting--ledger)
- [Tax Computation](#tax-computation)
- [Estate Planning & Actuarial Modeling](#estate-planning--actuarial-modeling)
- [Compliance, KYC & AML](#compliance-kyc--aml)
- [Backtesting Frameworks](#backtesting-frameworks)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

## Portfolio & Asset Management

Allocation, construction, and optimization of investment portfolios.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [FinQuant](https://github.com/fmilthaler/FinQuant) | ![Stars](https://img.shields.io/github/stars/fmilthaler/FinQuant?style=flat-square) | Tools for portfolio management, analysis, and optimization workflows |
| Python | [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) | ![Stars](https://img.shields.io/github/stars/robertmartin8/PyPortfolioOpt?style=flat-square) | Financial portfolio optimization, including classical efficient frontier and advanced methods |
| Python | [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) | ![Stars](https://img.shields.io/github/stars/dcajasn/Riskfolio-Lib?style=flat-square) | Portfolio optimization and quantitative strategic asset allocation |
| Python | [skfolio](https://github.com/skfolio/skfolio) | ![Stars](https://img.shields.io/github/stars/skfolio/skfolio?style=flat-square) | Portfolio optimization built on top of scikit-learn |

*No actively-maintained, dedicated portfolio-construction/optimization libraries were found for Go or Rust at the time of writing.*

## Risk & Performance Analytics

Risk metrics, performance attribution, and return analytics.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [empyrical-reloaded](https://github.com/stefan-jansen/empyrical-reloaded) | ![Stars](https://img.shields.io/github/stars/stefan-jansen/empyrical-reloaded?style=flat-square) | Maintained fork of Quantopian's common financial risk and performance metrics library |
| Python | [pyfolio-reloaded](https://github.com/stefan-jansen/pyfolio-reloaded) | ![Stars](https://img.shields.io/github/stars/stefan-jansen/pyfolio-reloaded?style=flat-square) | Maintained fork of Quantopian's portfolio and risk analytics library |
| Python | [quantstats](https://github.com/ranaroussi/quantstats) | ![Stars](https://img.shields.io/github/stars/ranaroussi/quantstats?style=flat-square) | Portfolio analytics for quants: performance/risk metrics and tearsheets |
| Go | [gonum](https://github.com/gonum/gonum) | ![Stars](https://img.shields.io/github/stars/gonum/gonum?style=flat-square) | Numeric libraries for Go, including statistics and matrix operations used to build risk metrics |
| Rust | [statrs](https://github.com/statrs-dev/statrs) | ![Stars](https://img.shields.io/github/stars/statrs-dev/statrs?style=flat-square) | Statistical distributions and computation, a common building block for risk analytics |

## Financial Data & Market Access

Market data downloaders and brokerage/exchange API clients.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [alpaca-py](https://github.com/alpacahq/alpaca-py) | ![Stars](https://img.shields.io/github/stars/alpacahq/alpaca-py?style=flat-square) | Official Python SDK for Alpaca's trading and market data API |
| Python | [ccxt](https://github.com/ccxt/ccxt) | ![Stars](https://img.shields.io/github/stars/ccxt/ccxt?style=flat-square) | Cryptocurrency trading API library with support for many exchanges |
| Python | [pandas-datareader](https://github.com/pydata/pandas-datareader) | ![Stars](https://img.shields.io/github/stars/pydata/pandas-datareader?style=flat-square) | Pulls data from various financial data sources into pandas data structures |
| Python | [yfinance](https://github.com/ranaroussi/yfinance) | ![Stars](https://img.shields.io/github/stars/ranaroussi/yfinance?style=flat-square) | Yahoo! Finance market data downloader |
| Go | [alpaca-trade-api-go](https://github.com/alpacahq/alpaca-trade-api-go) | ![Stars](https://img.shields.io/github/stars/alpacahq/alpaca-trade-api-go?style=flat-square) | Official Go client for Alpaca's trading and market data API |
| Go | [finance-go](https://github.com/piquette/finance-go) | ![Stars](https://img.shields.io/github/stars/piquette/finance-go?style=flat-square) | Financial markets data library implemented in Go |
| Go | [go-quote](https://github.com/markcheno/go-quote) | ![Stars](https://img.shields.io/github/stars/markcheno/go-quote?style=flat-square) | Historical quote downloader for Yahoo Finance, Coinbase, Binance, and more |
| Rust | [apca](https://github.com/d-e-s-o/apca) | ![Stars](https://img.shields.io/github/stars/d-e-s-o/apca?style=flat-square) | Async crate for interacting with the Alpaca trading and market data API |
| Rust | [yahoo_finance_api](https://github.com/xemwebe/yahoo_finance_api) | ![Stars](https://img.shields.io/github/stars/xemwebe/yahoo_finance_api?style=flat-square) | Rust adapter for fetching historical market data quotes from Yahoo Finance |

## Quantitative Finance & Derivatives Pricing

Pricing engines and quantitative-finance toolkits.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [FinancePy](https://github.com/domokane/FinancePy) | ![Stars](https://img.shields.io/github/stars/domokane/FinancePy?style=flat-square) | Pricing and risk-management of financial derivatives |
| Python | [gs-quant](https://github.com/goldmansachs/gs-quant) | ![Stars](https://img.shields.io/github/stars/goldmansachs/gs-quant?style=flat-square) | Goldman Sachs' Python toolkit for quantitative finance |
| Python | [vollib](https://github.com/vollib/vollib) | ![Stars](https://img.shields.io/github/stars/vollib/vollib?style=flat-square) | Calculates option prices, implied volatility, and Greeks |
| Rust | [quantrs](https://github.com/carlobortolan/quantrs) | ![Stars](https://img.shields.io/github/stars/carlobortolan/quantrs?style=flat-square) | Fast, intuitive library for options pricing and derivatives |
| Rust | [RustQuant](https://github.com/avhz/RustQuant) | ![Stars](https://img.shields.io/github/stars/avhz/RustQuant?style=flat-square) | Quantitative finance: option pricing, stochastic processes, automatic differentiation |

*No actively-maintained, dedicated derivatives-pricing libraries were found for Go at the time of writing.*

## Accounting & Ledger

Double-entry bookkeeping and general-ledger tooling.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [beancount](https://github.com/beancount/beancount) | ![Stars](https://img.shields.io/github/stars/beancount/beancount?style=flat-square) | Double-entry accounting from plain-text files |
| Go | [ledger](https://github.com/howeyc/ledger) | ![Stars](https://img.shields.io/github/stars/howeyc/ledger?style=flat-square) | Command-line double-entry accounting program, a Go take on `ledger-cli` |
| Rust | [rustledger](https://github.com/rustledger/rustledger) | ![Stars](https://img.shields.io/github/stars/rustledger/rustledger?style=flat-square) | Modern plain-text accounting engine, Beancount-file compatible |

## Tax Computation

Tax calculation and modeling libraries.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [Tax-Calculator](https://github.com/PSLmodels/Tax-Calculator) | ![Stars](https://img.shields.io/github/stars/PSLmodels/Tax-Calculator?style=flat-square) | USA federal individual income and payroll tax microsimulation model |
| Python | [tenforty](https://github.com/mmacpherson/tenforty) | ![Stars](https://img.shields.io/github/stars/mmacpherson/tenforty?style=flat-square) | Computes US federal and some state taxes, built on Open Tax Solver |

*No actively-maintained, dedicated tax-computation libraries were found for Go or Rust at the time of writing.*

## Estate Planning & Actuarial Modeling

Dedicated open-source software for estate planning (wills, trusts, probate) is essentially nonexistent; the closest actively-developed adjacent domain is actuarial and life-contingency modeling (mortality, annuities, life insurance), which underpins much of estate and legacy planning analysis.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [lifelib](https://github.com/lifelib-dev/lifelib) | ![Stars](https://img.shields.io/github/stars/lifelib-dev/lifelib?style=flat-square) | Actuarial models, tools, and examples for life insurance and annuities |
| Python | [lifeactuary](https://github.com/parcr/lifeactuary) | ![Stars](https://img.shields.io/github/stars/parcr/lifeactuary?style=flat-square) | Actuarial mathematics for life contingencies and financial mathematics |
| Python | [pyliferisk](https://github.com/franciscogarate/pyliferisk) | ![Stars](https://img.shields.io/github/stars/franciscogarate/pyliferisk?style=flat-square) | Life and actuarial calculations using International Actuarial Notation |

*No actively-maintained Go or Rust libraries in this space were found at the time of writing.*

## Compliance, KYC & AML

Sanctions/PEP screening and regulatory-compliance data tooling.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [followthemoney](https://github.com/opensanctions/followthemoney) | ![Stars](https://img.shields.io/github/stars/opensanctions/followthemoney?style=flat-square) | Entity and relationship data model underlying OpenSanctions, useful for KYC data pipelines |
| Python | [yente](https://github.com/opensanctions/yente) | ![Stars](https://img.shields.io/github/stars/opensanctions/yente?style=flat-square) | Self-hostable screening API for OpenSanctions data: entity search and bulk matching |

*No actively-maintained, dedicated compliance/KYC/AML libraries were found for Go or Rust at the time of writing.*

## Backtesting Frameworks

Strategy backtesting and (often paired) live/paper-trading engines.

| Language | Package | Stars | Description |
|---|---|---|---|
| Python | [backtrader](https://github.com/backtrader/backtrader) | ![Stars](https://img.shields.io/github/stars/backtrader/backtrader?style=flat-square) | Python backtesting library for trading strategies |
| Python | [nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | ![Stars](https://img.shields.io/github/stars/nautechsystems/nautilus_trader?style=flat-square) | High-performance algorithmic trading platform and event-driven backtester (Rust core, Python API) |
| Python | [vectorbt](https://github.com/polakowo/vectorbt) | ![Stars](https://img.shields.io/github/stars/polakowo/vectorbt?style=flat-square) | Vectorized toolkit for backtesting, algorithmic trading, and research |
| Python | [zipline-reloaded](https://github.com/stefan-jansen/zipline-reloaded) | ![Stars](https://img.shields.io/github/stars/stefan-jansen/zipline-reloaded?style=flat-square) | Maintained fork of Quantopian's pythonic algorithmic trading library |
| Go | [gobacktest](https://github.com/dirkolbrich/gobacktest) | ![Stars](https://img.shields.io/github/stars/dirkolbrich/gobacktest?style=flat-square) | Event-driven backtesting framework written in Go |
| Rust | [barter-rs](https://github.com/barter-rs/barter-rs) | ![Stars](https://img.shields.io/github/stars/barter-rs/barter-rs?style=flat-square) | Open-source framework for building event-driven live-trading and backtesting systems |

## Related Awesome Lists

- [awesome-quant](https://github.com/wilsonfreitas/awesome-quant) — the broader, language-agnostic quantitative finance list this repo draws context from
- [awesome-go-quant](https://github.com/goex-top/awesome-go-quant) — Go-specific quant/finance libraries
- [plaintextaccounting.org](https://plaintextaccounting.org/) — the plain-text accounting ecosystem (Ledger, hledger, Beancount, and their ports)

## Contributing

Contributions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for inclusion criteria and the pull request checklist.

## License

[CC0](LICENSE) — to the extent possible under law, the authors have waived all copyright and related rights to this list.
