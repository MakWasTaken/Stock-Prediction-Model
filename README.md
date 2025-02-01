# Stock Prediction Model (v0.7.10)

IMPORTANT NOTE: THE MODEL HAS CEASED FUNCTIONING DUE TO INCOMPATIBLE LIBRARY VERSIONS OR OTHER ERRORS. THIS PROJECT IS NOW ON HIATUS.

This is a stock prediction model built using a LSTM (Long Short-Term Memory) neural network. The model is designed to predict stock prices based on historical data, specifically focusing on the closing prices of the stock.

## Introduction
The stock prediction model uses historical stock data from Yahoo Finance to train an LSTM neural network. The model is trained on a dataset of stock prices from 2014 to 2024 (users can change this easily) and is capable of predicting future stock prices based on past trends.

## Features
- **Data Preprocessing**: The model uses `MinMaxScaler` to normalize the data, making it suitable for training the LSTM network.
- **LSTM Network**: The model employs a two-layer LSTM network to capture temporal dependencies in the stock data.
- **Cross-Validation**: The model is evaluated using K-Fold cross-validation to ensure robustness.
- **Prediction Visualization**: The model's predictions are visualized alongside the actual stock prices using Matplotlib.
- **Performance Metrics**: The model's performance is evaluated using R² score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
