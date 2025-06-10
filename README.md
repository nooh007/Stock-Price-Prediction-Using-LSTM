# Stock-Price-Prediction-Using-LSTM

This repository contains the code and resources for predicting stock market trends using Long Short-Term Memory (LSTM) neural networks.

# Project Overview 

In this project, we leverage Google stock market data from the year 2010 upto 2024 to train an LSTM model. The model learns from past price patterns and trends, enabling it to predict future stock prices. The LSTM network is specifically designed to capture long-term dependencies and has proven to be effective in time series forecasting tasks.

# Dataset

The dataset is readily avaialble online in yfinance, following is the command to import the dataset properly, make sure to pip install yfinance in your terminal (virtual environment):
```
import yfinance as yf

# Fetch historical data for Google stock (GOOG)
df = yf.download('GOOG', start='2010-01-01', end='2024-12-01')

# Display the first few rows of the data
print(df.head())

```
