# Fawry (FWRY.CA) Stock Price & Sentiment Trend Analysis

## Overview
This project explores the relationship between Fawry's (EGX: FWRY) stock price behavior and key company news events from 2022–2026, using Python.

## Data
- Price data: Historical daily prices pulled via yfinance (ticker: `FWRY.CA`)
- Events data: Curated list of real Fawry news (earnings releases, partnerships, leadership changes), manually labeled by sentiment (positive / negative / neutral)

## Methods
- Calculated daily returns and 30-day rolling volatility
- Overlaid key events on price and volatility charts
- Combined into a final two-panel dashboard for comparison

## Key Findings
- Fawry showed a strong long-term uptrend from 2022–2026
- Highest volatility occurred in early 2024, declining steadily through 2025–2026 despite continued price growth
- Most curated events were positive (earnings beats, partnerships), reflecting Fawry's strong business performance over the period

## Limitations
- Event sentiment was manually curated, not derived from large-scale news scraping or NLP sentiment scoring
- Sample skews positive — limited ability to test how negative news affects price/volatility
- Event dates approximate; some snapped to nearest trading day due to market holidays

## Tools
python, pandas, matplotlib, yfinance

## Output
fawry_sentiment_dashboard.png — combined price + volatility + event dashboard
