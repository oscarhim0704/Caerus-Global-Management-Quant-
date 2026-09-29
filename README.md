# Caerus-Global-Management-Quant

## BTC Perpetual-Futures Lead–Lag Research

A quantitative research project completed during the Caerus Global Management Summer Analyst Training Program. I investigated whether short-term price movements in BTC perpetual futures on Binance and Hyperliquid could be used as a cross-venue trading signal.

## Research question

Does a BTC lead–lag signal remain viable after accounting for transaction fees, market impact, execution latency, and position constraints?

## What I built

- A Python backtesting framework for testing cross-venue lead–lag signals.
- Signal-entry and exit logic using a rolling z-score.
- Cost and risk checks covering four-leg execution costs, depth-constrained sizing, and liquidation risk.

## Key finding

The signal did not show a viable edge once the costs and execution assumptions in this backtest were applied. During validation, I found and corrected a z-score exit bug that closed positions early and overstated simulated returns.

## Tools

Python, pandas, NumPy
