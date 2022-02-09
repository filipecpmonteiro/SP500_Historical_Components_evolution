# R code to build snapshot of the S&P500 historical daily components since 1/1/2000 (with current updated tickers)

This file contains a R code to build the daily S&P 500 components since 1/1/2000
The output is a matrix:
i. rows are tickers
ii. columns are dates
iii. matrix has 1's if ticker was present in that day, or 0's otherwise

The source is a combination of Wikipedia, Yahoo Finance, Bloomberg and extensive research I did on a stock-by-stock basis (press, etc.) to make all sources consistent
