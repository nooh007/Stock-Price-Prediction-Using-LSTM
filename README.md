# Stock-Price-Prediction-Using-LSTM

This repository contains the code and resources for predicting stock market trends using Long Short-Term Memory (LSTM) neural networks.

# Project Overview 

The project is implemented in GOOGLECOLAB, We have used Google stock market data from the year 2010 upto 2024 to train an LSTM model. The model learns from past price patterns and trends, enabling it to predict future stock prices. The LSTM network is specifically designed to capture long-term dependencies and has proven to be effective in time series forecasting tasks.

# Dataset

The dataset is readily avaialble from yfinance library, following is the command to import the dataset properly, make sure to pip install yfinance in your terminal (virtual environment):
```
import yfinance as yf

# Fetch historical data for Google stock (GOOG)
df = yf.download('GOOG', start='2010-01-01', end='2024-12-01')

# Display the first few rows of the data
print(df.head())

```

# Model Training
The LSTM model is built using deep learning frameworks like TensorFlow or PyTorch. We train the model on the training dataset, adjusting hyperparameters such as the number of hidden layers, the number of neurons per layer, and the learning rate. 

# Model Evaluation and Metrics
Once the model is trained, we evaluate its performance on the testing dataset. We compute various metrics such as mean squared error (MSE),  root mean squared error (RMSE), and mean absolute error (MAE), R2 score, and mape to assess the model's accuracy. We visualize the predicted stock prices alongside the actual prices to gain insights into the model's performance.

# Results
## model Predictions vs Groundtruth
</br>
<img src="https://github.com/nooh007/Stock-Price-Prediction-Using-LSTM/blob/main/Images/lstm%20prediction%20.png" width="300">
<img src="https://github.com/nooh007/Stock-Price-Prediction-Using-LSTM/blob/main/Images/rnn%20prediction%20graph.png" width="300">
</br>

## model Performance metrics
</br>
<img src="" width="300">
<img src="" width="300">
</br>



</br>
