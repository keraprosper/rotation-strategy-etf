# rotation-strategy-etf

OVERVIEW ~

This project is a ETF rotation strategy using python and historical data pulled from Yahoo Finance. It selects top performing ETFs from the 3 most recent months and rebalances monthly. This process aims to perform better than a traditional buy-and-hold benchmark.

LOGIC ~

universe: SPY, QQQ, IWM, EFA, EEM, XLK, XLF, XLE
frequency: monthly
ranking: most recent 3 months
allocation: equal-weight top 3 ETFs

TOOLS USED ~

1. Jupyter Notebook 
2. Python, pandas, NumPy, yfinance, and matplotlib

FILES ~
- notebook/etf_strategy.ipynb for complete code 
- src for modular strategy components 
- README.md for project overview 

PERFORMANCE ANALYSIS ~

format: matric | rotation strategy | SPY benchmark

CAGR         | 5.93%   | 13.57%
Sharpe Ratio | 0.85    | 0.83
Max Drawdown | -9.17%  | -23.93%

Thank you for viewing! <3
