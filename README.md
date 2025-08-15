# Dividend Gap Strategy

Research and backtest of a dividend gap trading strategy on the Russian equity market (2015–2025).  
Includes a Jupyter Notebook with analysis code and a PDF presentation summarizing the results.

## Contents
- **dividend_gap_strategy.ipynb** — data loading, calculations, and visualizations
- **Presentation.pdf** — summary of results, charts, and performance metrics

## Highlights
- Dataset of 1,500 dividend events
- Entry: buy on record date  
  Exit: sell on first ex-dividend date
- Hypothesis: market underestimates dividends by ~13% tax, causing partial rebound
- Performance: WinRate 70%, Sharpe 1.6, Profit Factor 2.6
- Outperformed MCFTR benchmark by 0.65 p.p.
