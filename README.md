# Algorithmic-Trading: 

## Version 1: 

This script follows the DataCamp tutorial on visualising stock returns as time series data using the AlphaVantage API. It covers some of the most common financial analyses, like moving windows and volatility calcualtion using the Python pandas package. This script also develops a simple momentum strategy, backtests it, and optimises it to aid its performance in the future. 

There are some clear limitations to this script, as it only uses one stock across 100 days, which is far too short and narrow to draw any meaningful conclusions. Unfortunately, I am limited by the AlphaVantage API, which restricts me to using 100 days of data for each ticker.


## Version 2: 

This script builds on the earlier version, but still following the DataCamp tutorial on visualising stock returns as time series data using the yfinance package in Python. It covers some of the most common financial analyses, like moving windows, volatility, Sharpe ratio, and maximum drawdown calculations using the pandas package. The advantages of using yfinance are clear, as I am no longer limited to using 100 days of data for each ticker, and am able to make many more calls.

This script also develops a simple momentum strategy, backtests it, and optimises it to aid its performance in the future. In particular, it examines common defence stocks and attempts to build a moving-average strategy for both a single stock and a portfolio of the top 10 defence stocks. 

## Version 3: 

This script builds on Version 2, delving into other trading strategies, such as using Bollinger Bands for a portfolio of the top 10 defence stocks. Once again, I backtest the different strategies and evaluate them using metrics like Maximum Drawdown.  

*DISCLAIMER: AI tools such as Claude and ChatGPT were used to fix coding errors, and suggest improvements to optimise the efficiency of the script.* 



 
