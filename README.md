
# Stock Market Data Analysis EDA Project

## Introduction:
Stock Market Analysis and Prediction is the project related to Exploratory data analysis(EDA), Data visualization and Predictive analysis using data, provided by The Investors Exchange (IEX). I looked at **real-time financial data** from the stock market. I have used python libraries to get stock information, visualize different aspects of it, and finally I worked at a few ways of analyzing the risk of a stock, based on its previous performance history. I have also used statistical method called **Monte Carlo Method** to predict future stock prices.


## Dataset Description
- **Date**: Date set by a company on which the investor must own shares.
- **Open**: Open refers the starting period (day) of trading.
- **High**: High refers highest price at which a stock is traded during a period.
- **Low**: Low refers the minimum price of a stock in a period.
- **Closed**: Closed refers the price of an individual stock when the stock exchange closed shop for the day.
- **Adj Close**: Adj Close refers Adjusted closing price.
- **Volume**: Volume refers an indicator of liquidity.

### We'll be answering the following questions by using Exploratory Data Analysis:

1. What was the change in price of the stock over time?
2. What was the daily return of the stock on average?
3. What was the moving average of the various stocks?
4. What was the correlation between different stocks 'closing prices'?
5. What was the correlation between different stocks 'daily returns'?
6. How much value do we put at risk by investing in a particular stock?
7. How can we attempt to predict future stock behavior?

### Basic Analysis of Stock Information
In this section we'll go over how to handle requesting stock information with pandas and how to analyze basic attributes of a stock.
# Workflow
## Import Python Modules
1. **yfinance**: 
A library to download financial market data from Yahoo Finance.This can be used to download stock market data from India as well as other global market.

2. **pandas_datareader**

Remote data access for pandas to extract data from various Internet sources into a pandas DataFrame.

3. **Load Dataset**
Download the Historical stock data for specific company listed in the Indian Stock Market using **yfinance** library.
- Here I extract reliance finace data from last 1 years.

Ex: 1. **IEX**
- The Investors Exchange (IEX) provides a wide range of data through an API.
- Historical stock prices are available for up to 15 years.
## Statistical Method
- **Monte Carlo method**
A Monte Carlo simulation is an attempt to predict the future many times over. At the end of the simulation, thousands or millions of "random trials" produce a distribution of outcomes that can be analyzed.
Read more at 

https://www.investopedia.com/articles/07/montecarlo.asp
## Authors

- [swati khedekar](https://github.com/Swatikhedekar/Stock-Market-Data-Analysis-EDA-project)

