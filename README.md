# Market-Analysis-Project
Using Hidden Markov Models (HMM) and Long Short-Term Memory (LSTM) Models for evaluation and prediction of the New York Stock Exchange.

## DISCLAIMER:
This project seeks to identify if it is even possible to make predictions. 
Nothing covered within this project / presentation is financial advice. Be safe with your money.​


# 
This work was done for ELE-391 at the Univeristy of Rhode Island, taught by Dr. Chiovaro.

Work done by Garrett Kemper, Richard Buckley, and Daniel Sanguino

# Purpose of Model

The New York Stock Exchange is highly volatile and is significantly impacted by various numerical indicators. There is strong demand to evaluate and predict the state of the market as it has significant implications in all industries across the United States. The aim of this project is to use machine learning models to examine and identify patterns, trends, and correlations within the financial markets, to provide insights into market behavior. By leveraging time-series data, economic indicators and other financial variables, we seek to detect market movements and assess the degree of predictability within the market.

To solve this problem, two different models will be trained and their results will be compared to evaluate their ability to make these predictions. The models that will be used are a Hidden Markov Model (HMM) and a Long Short-Term Memory (LSTM) Model.

This project correlates with the field of computer engineering due to a high demand for electrical and computer engineers in the financial technologies sector. Many major companies are highly interested in developing FPGAs for algorithmic trading. Additionally, combining business skills with engineering often provides significant value to many companies. Although the demand is relatively new, computer engineers are hired throughout the industry, whether it is hardware, software, or machine learning.

# Use of Data

The data used for this project was extracted using yfinance, a python library that provides market data from Yahoo! Finance’s API. Further data was sourced from DiscountingCashFlows for financial statements and AlphaVantage for sentiment analysis. The stock data from yfinance provides a significant amount of data. For this application, data from Apple Inc (AAPL, NASDAQ). This subset of data contains 720 instances with 49 features.  Each instance represents one business day of that stock.

# Instructions

The folder attached is intended to live in a google drive and run in Google Colab.

Some editing of directories in code may be required to run.

There is a variables section which contains various constants used throughout the code, including the Ticker.

Changing these variables can alter the model to work for different stocks and markets.
