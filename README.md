# Algorithmic-Trading

This repository contains the foundation for developing trading strategies, emphasizing the implementation of mathematical formulas and the analysis of financial market data to identify opportunities for data-driven trading decisions

## Description

This project provides a detailed framework for trading strategy development and evaluation:

Portfolio Analysis: Conducts a thorough risk analysis of a ten-stock portfolio. Key metrics include:

* Ticker
* Portfolio Weight (equal weighting)
* Annualized Volatility (trailing 3 months)
* Beta against major indices (SPY, IWM, DIA, trailing 12 months)
* Average and Maximum Weekly Drawdown

Efficient Frontier Calculation: Applies Markowitz’s mean-variance theory to compute the efficient frontier and determine optimal portfolio weights. This involves:

* Calculating mean, variance, and correlation matrix for all assets
* Developing and plotting the efficient frontier to optimize portfolio performance

Algorithmic Trading: Uses Berry Cox’s price momentum factors to select and backtest a long-short portfolio algorithm. Includes:

* Calculation of price momentum factors for each asset
* Monthly z-factor score calculation
* Backtesting performance over a 5-year period, with visualizations of returns and comparisons against benchmarks

The aim is to offer a framework for constructing, testing, and refining trading strategies, leveraging historical data and financial models to drive data-driven trading decisions.


