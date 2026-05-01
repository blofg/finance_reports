# finance_reports

Automated HTML reports built with R and published via GitHub Pages.
All reports are generated from the [`finance_analysis`](https://github.com/your-username/finance_analysis) pipeline — covering macro indicators, equity valuations, monetary policy, stress & volatility indices, bond markets & yield curves, freight, geopolitical risk, currency dynamics, and crypto across major economies, as well as individual share analysis, technical indicators, and financial statements.


## Repository Structure

```
finance_reports/
│
├── index.html                          # Landing page — report navigator
│
└── reports/
    ├── us_report_html.html             # United States
    ├── eu_report_html.html             # Euro Area
    ├── ch_report_html.html             # Switzerland
    ├── wrl_report_html.html            # World Overview
    ├── equity_index_report_html.html   # Equity Index
    ├── key_indices_and_indicators_report_html.html  # Key Indices & Indicators
    ├── gold_fundamentals_report_html.html           # Gold Fundamentals
    ├── crypto_report_html.html         # Crypto
    ├── bond_market_report_html.html    # Bond Market
    └── share/
        └── mag7/
            ├── magnificent_aapl_report_html.html   # Apple
            ├── magnificent_msft_report_html.html   # Microsoft
            ├── magnificent_nvda_report_html.html   # Nvidia
            ├── magnificent_googl_report_html.html  # Alphabet
            ├── magnificent_amzn_report_html.html   # Amazon
            ├── magnificent_meta_report_html.html   # Meta
            └── magnificent_tsla_report_html.html   # Tesla
```

## Reports

### Geo Reports
Macroeconomic and financial reports across major economies:

- **United States** (`us_report_html.html`)
- **Euro Area** (`eu_report_html.html`)
- **Switzerland** (`ch_report_html.html`)
- **World Overview** (`wrl_report_html.html`)

### Market Reports
Financial and marekt reports:

- **Equity Index** (`equity_index_report_html.html`)
- **Key Indices & Indicators** (`key_indices_and_indicators_report_html.html`)
- **Gold Fundamentals** (`gold_fundamentals_report_html.html`)
- **Crypto** (`crypto_report_html.html`)
- **Bond Market** (`bond_market_report_html.html`)

### Share Reports — Magnificent 7
Individual equity reports with price history, technical indicators.

- **Apple** (`share/mag7/magnificent_aapl_report_html.html`)
- **Microsoft** (`share/mag7/magnificent_msft_report_html.html`)
- **Nvidia** (`share/mag7/magnificent_nvda_report_html.html`)
- **Alphabet** (`share/mag7/magnificent_googl_report_html.html`)
- **Amazon** (`share/mag7/magnificent_amzn_report_html.html`)
- **Meta** (`share/mag7/magnificent_meta_report_html.html`)
- **Tesla** (`share/mag7/magnificent_tsla_report_html.html`)


## How reports are generated

All `.html` files in this repository are rendered automatically by the [`finance_analysis`](https://github.com/your-username/finance_analysis) R pipeline and pushed here via `publish.R`. Do not edit them manually — any changes will be overwritten on the next run.
