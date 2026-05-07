U.S. Retail Sales Time Series Forecasting
Authors
Hamdha, Hemara, Lakshika

HND in Data Science, NIBM

Project Overview
This project focuses on analyzing and forecasting monthly retail sales data using advanced statistical time series modeling in R. The goal was to identify seasonal patterns and trends in the retail sector to project future sales volumes with high accuracy.

Technical Workflow
Exploratory Data Analysis (EDA): Visualized historical trends and performed seasonal decomposition to separate the trend, seasonality, and random noise components.

Stationarity Testing: Applied the Augmented Dickey-Fuller (ADF) test and utilized differencing techniques to transform the data into a stationary state.

Model Selection: Evaluated Autocorrelation (ACF) and Partial Autocorrelation (PACF) plots to determine the optimal parameters for the SARIMA (Seasonal Autoregressive Integrated Moving Average) model.

Forecasting: Generated a 24-month sales forecast with 80% and 95% confidence intervals, accounting for year-end holiday spikes and seasonal fluctuations.

Key Results
The model successfully captured the consistent upward trend in retail sales while adjusting for significant seasonal volatility. The final forecast provides a data-driven outlook for inventory and revenue planning through 2027.

Technical Stack
Language: R

Libraries: forecast, tseries, ggplot2

Model: SARIMA (Seasonal ARIMA)
