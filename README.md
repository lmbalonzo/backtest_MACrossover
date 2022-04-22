# Backtesting An Equity Using MA Crossover
# Objectives:
  1. Model historical performance of a stock (Benchmark)
  2. Model performance of a Moving Average Crossover Trading Strategy (System)
  3. Compare the Returns and Drawdowns of benchmark and system
# Moving Average Crossover Trading Strategy
  Long signal is when fast moving average is higher than slow moving average
# Libraries Used:
  - pandas_datareader
  - numpy
  - datetime
  - matplotlib
# Modifications
  - Used faster MAs to simulate shorter term trading
  - Shortened time period of observation
  - Modelled TSLA
# Future Improvements:
  - Add other criteria for long signal (ex: minumum ADX)
  - Compare returns and drawdowns using different MAs
  - Compare different stocks
# Reference:
  - https://www.youtube.com/watch?v=ymQ4WhO5Xc0
  - https://www.investopedia.com/articles/active-trading/052014/how-use-moving-average-buy-stocks.asp
