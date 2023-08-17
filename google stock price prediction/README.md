# Stock Price Prediction using LSTM  
This repository contains code for predicting stock prices using a Long Short-Term Memory (LSTM) neural network. The code uses historical stock price data from Google and trains an LSTM model to predict future stock prices.
## Introduction  
This repository contains code for predicting stock prices using a Long Short-Term Memory (LSTM) neural network. The code utilizes historical stock price data from Google and trains an LSTM model to forecast future stock prices.

## Objective  
The main goal of this project is to demonstrate the application of LSTM neural networks in predicting stock prices based on historical data.

## Attributes  
* Training Data: Historical stock price data for Google is used for training the LSTM model.
* Testing Data: Additional historical stock price data is used to test the trained model's predictive capabilities.
* LSTM Neural Network: The model is built using a series of LSTM layers with dropout for regularization.
* Feature Scaling: MinMaxScaler is employed to scale the stock price data to a range between 0 and 1.
* Loss Function: The model is compiled using the mean squared error loss and optimized using the Adam optimizer.
* Visualization: The actual and predicted stock prices are visualized using matplotlib.
## Library  
numpy
pandas
matplotlib
scikit-learn
keras (with TensorFlow backend)
These libraries are used for data manipulation, visualization, and building the LSTM model.

## Methods  
**LSTM**


## Result  
The result of the project is a visualization that compares the actual stock prices with the predicted stock prices using the trained LSTM model. The plotted graph illustrates the model's performance in predicting stock prices based on historical trends.
