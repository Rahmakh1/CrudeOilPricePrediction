# Crude Oil Price Analysis and Prediction
This project aims to analyze and predict crude oil prices using time series forecasting techniques. Developed as part of the "Signal Theory and Systems" course, this project explores traditional and neural network models to improve forecasting accuracy for financial applications.

## Project Overview
This project focuses on time series forecasting using both statistical and neural network models, applied to crude oil price data. The project is divided into two main case studies:

Statistical Models: AR, MA, ARMA, and ARIMA models are used to capture the time-series structure of oil price data.
Deep Learning Models: An LSTM (Long Short-Term Memory) model is applied to leverage sequence learning for more complex patterns.
## Authors
-Rahma Kharrat
-Myriam El Amri

## Data
The crude oil price data was sourced using the yfinance library, which retrieves financial data from Yahoo Finance. The dataset includes:

Opening, high, low, and closing prices
Volume of transactions
## Methodology
### 1. Time Series Analysis
Data Visualization: Initial visualization to identify trends, seasonality, and stationarity.
Stationarity Testing: Augmented Dickey-Fuller (ADF) and KPSS tests to confirm stationarity.
Time Series Decomposition: Analysis of trend, seasonality, and noise components.
### 2. Statistical Models
AR, MA, ARMA, ARIMA: Implemented and evaluated for crude oil data prediction.
Model Selection: Based on ACF and PACF plots, the models were tuned for optimal order and lag parameters.
### 3. LSTM Model
Configuration: A sequential LSTM model is configured with two LSTM layers and a dense output layer.
Evaluation: The model is evaluated on Mean Absolute Error (MAE) and Root Mean Square Error (RMSE).
### Results
Statistical Models: The ARIMA model provided the best results among statistical models with relatively low prediction error.
LSTM Model: The LSTM model achieved a notable prediction accuracy for longer-term forecasts, showcasing deep learning’s advantage in capturing complex time dependencies.




