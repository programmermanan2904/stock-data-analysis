Time Series Analysis – Stock Prices (Task 3)
Overview
This project is part of the Code Veda learning series. The objective is to analyze stock price data, identify patterns, and understand time-series components like trend, seasonality, and residuals. Additionally, we apply moving average smoothing to better visualize long-term patterns.

Objectives
Plot time-series data and identify patterns.

Decompose the series into trend, seasonality, and residuals using statsmodels.

Apply moving average smoothing to highlight overall trends.

Dataset
Name: Stock Prices Dataset

Columns: date, symbol, open, high, low, close, volume

Frequency: Daily stock prices (multiple companies)

Steps Performed
Load and clean data

Convert date to datetime format

Filter data for one stock (e.g., AAPL)

Sort by date and set date as index

Visualization

Plot raw closing price over time

Decomposition

Decompose into trend, seasonality, and residuals using additive model

Moving Average

Apply 30-day rolling average to smooth short-term fluctuations

Technologies Used
Python 3

Pandas (data handling)

Matplotlib & Seaborn (visualization)

Statsmodels (time-series decomposition)

