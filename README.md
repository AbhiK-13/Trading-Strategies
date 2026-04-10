# Trading-Strategies: 

The "Algorithmic Trading" repository delves into the basics of algorithmic trading, slowly becoming more advanced with each script version. I start off with basic EDA of stocks using yfinance in Python, and transition slowly to using techniques like Bollinger bands and using a Markov regime-switching framework to enhance the value of my simulated portfolio. 

## Version 1: 

This script follows the DataCamp tutorial on visualising stock returns as time series data using the AlphaVantage API. It covers some of the most common financial analyses, like moving windows and volatility calcualtion using the Python pandas package. This script also develops a simple momentum strategy, backtests it, and optimises it to aid its performance in the future. 

There are some clear limitations to this script, as it only uses one stock across 100 days, which is far too short and narrow to draw any meaningful conclusions. Unfortunately, I am limited by the AlphaVantage API, which restricts me to using 100 days of data for each ticker.


## Version 2: 

This script builds on the earlier version, but still following the DataCamp tutorial on visualising stock returns as time series data using the yfinance package in Python. It covers some of the most common financial analyses, like moving windows, volatility, Sharpe ratio, and maximum drawdown calculations using the pandas package. The advantages of using yfinance are clear, as I am no longer limited to using 100 days of data for each ticker, and am able to make many more calls.

This script also develops a simple momentum strategy, backtests it, and optimises it to aid its performance in the future. In particular, it examines common defence stocks and attempts to build a moving-average strategy for both a single stock and a portfolio of the top 10 defence stocks. 

## Version 3: 

This script builds on Version 2, delving into other trading strategies, such as using Bollinger Bands for a portfolio of the top 10 defence stocks. Once again, I backtest the different strategies and evaluate them using metrics like Maximum Drawdown.  

*DISCLAIMER: AI tools such as Claude and ChatGPT were used to fix coding errors, and suggest improvements to optimise the efficiency of the script.* 

## Version 4: 

This script builds on Version 3, diving into the use of Markov regime-switching frameworks across multiple tickers. I more intensely apply the use of functions rather than blunt commands to make the general workflow more flexible. The general workflow is as follows: 

1) Downloading relevant data 
2) Plotting returns 
3) Undertaking stationarity tests 
4) Finding the best AR order for each ticker
5) Fitting a two-regime Markov model 
6) Undertaking diagnostic checks
7) Interpreting results
8) Plotting results through volatility comparisons, transition matrices, and regime scatter/probabilities 

Note that this work is based off of work by the author on the linked page (https://medium.com/@cemalozturk/a-markov-regime-switching-approach-to-characterizing-financial-time-series-a5226298f8e1), where I adapt their work towards a specific portfolio of multiple tickers at once. 


*DISCLAIMER: AI tools such as Claude and ChatGPT were used to fix coding errors, and suggest improvements to optimise the efficiency of the script.* 

