# CryptocurrencyTradingAlgorithm

Project Stack
Concept: How do we create a simple algorithmic trading strategy for cryptocurrency?

Timeline: April 2022

Language: Python

Libraries: Numpy, Pandas, MatPlotLib, YFinance

------
# About
Fiat currencies are methods of payment issued by the government, with central authority (ex. bank) to regulate usage, such as USD, CAD, etc. Cryptocurrencies, on the other hand, are decentralized forms of payment. Transactions are held in a ledger/database, secured cryptographically! Algorithmic trading is a Way to automate making decisions related to buying/selling assets on pre-programmed instructions.

As crypto can also be traded, this project is a basic introduction to the following:

- Fetching Cryptocurrency market prices and data

- Performing basic analysis of market behavior

- Implementing a simple algorithmic trading strategy

- Analyzing the performance of the trading algorithm

------
The project proceeds in the following steps:

1. Getting market data from yahoo finance database

2. Creating a visual price chart, showcasing price over time.

3. Performing basic analysis with plot moving averages. The moving average is calculated with a series of averages of subsets of the data, and helps better understand long-term price trends.

4. Identify Buy/Sell points. By crossing two simple moving averages - one with short sampling interval and one with a long interval, we can identify when to buy or sell, based on the movement of the two relative to one another.

5. Backtest Algorithm. Backtesting is to simulate running algorithm on historical data and computer metrics.

I backtested with the two year period of 2018-2019 BTC-USD data and an account of $10,000 USD, with certain assumptions made for testing purposes. (ex. Zero commission trades, etc.) I also plotted a ‘buy and hold’ strategy to serve as baseline for comparison. 
 
Overall, the trading algorithm appears to be feasible, even out-performing the baseline buy-and-hold strategy!
