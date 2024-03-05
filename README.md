# Ethereum Stock Price Prediction with LSTMs

This project aims to predict the price of Ethereum cryptocurrency using Long Short-Term Memory (LSTM) networks. The model utilizes hourly data to forecast the future price of Ethereum, offering insights to traders and investors.

## Introduction
Cryptocurrency markets, including Ethereum, exhibit high volatility, making them attractive yet challenging for investors. Predicting price movements can assist traders in making informed decisions and mitigating risks. This project leverages LSTM networks, a type of recurrent neural network (RNN), to capture temporal dependencies and patterns in Ethereum price data.

## Dataset
The dataset used for training and evaluation consists of hourly Ethereum price data collected from reliable sources. It includes features such as opening price, closing price, highest price, lowest price, and trading volume. The dataset is preprocessed to handle missing values, scale features, and create input sequences suitable for LSTM training.

## Model Architecture
The LSTM model architecture comprises multiple LSTM layers followed by fully connected layers for regression. The model learns to predict future Ethereum prices based on historical price data. Hyperparameters such as the number of LSTM units, learning rate, and batch size are tuned to optimize performance and prevent overfitting.

## Dependencies
Python 3.x
TensorFlow 2.x
NumPy
Pandas
Matplotlib

## Results
The performance of the LSTM model is evaluated using metrics such as mean squared error (MSE), mean absolute error (MAE), and root mean squared error (RMSE). Visualizations are generated to compare actual Ethereum prices with predicted prices over time.

## Contributions
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
