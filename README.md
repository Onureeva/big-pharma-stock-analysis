# Big Pharma Stock Analysis: What Really Moves Prices?

Analyzing whether news sentiment actually drives pharmaceutical 
stock prices — or whether fundamentals and volatility tell a 
stronger story.

**Tickers:** LLY, MRK, AMGN, PFE (2023–2025)  
**Data:** yfinance, SEC/XBRL filings, news sentiment analysis

## Overview

In Big Pharma, stock prices are widely assumed to react strongly 
to news sentiment — FDA decisions, clinical trials, M&A 
announcements. This project tests that assumption by benchmarking 
sentiment signals against volatility, sector co-movement, and 
financial fundamentals.

**Hypothesis:** News sentiment ≠ price driver.  
Volatility, co-movement, and fundamentals = stronger signals.

## What's inside

- Indexed price performance comparison (base = 100)
- 30-day rolling volatility analysis with event window mapping
- LLY event windows: Q2 earnings, FDA approvals, clinical trial results
- Daily return correlation heatmap across 4 tickers
- Fundamentals vs. price: Revenue, Net Income, Dividends (LLY, PFE)
- News sentiment scoring and regression against returns

## Key Findings

- News sentiment shows no strong influence on daily returns
- Fundamentals are the primary driver of long-term price performance
- LLY outperforms (+200%) driven by GLP-1 product rerating — 
  price moves in step with revenue and net income expansion
- PFE de-rates as COVID vaccine tailwinds normalize
- MRK acts defensively with stable, low-volatility returns
- LLY partially decoupled from sector co-movement due to 
  company-specific catalysts (correlation 0.27 vs sector avg 0.41)

## Investment Positioning

| Ticker | Signal | Rationale |
|---|---|---|
| LLY | Overweight | GLP-1 growth driver, accept event-driven risk |
| MRK | Hold | Defensive, stable returns |
| AMGN | Hold | Balanced exposure, mid-pack performance |
| PFE | Selective | Post-COVID normalization ongoing |

## Tech stack

Python · yfinance · SEC/XBRL · pandas · matplotlib · seaborn · 
NLP sentiment analysis

## Author

Olga Nureeva · MS Business Analytics, Isenberg School of Management, UMass Amherst  
[LinkedIn](https://www.linkedin.com/in/olga-nureeva) · 
[GitHub](https://github.com/Onureeva)
