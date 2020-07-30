# Google Stock prediction using RNN
### In this project of predicting stock price I used an LSTM-based Recurrent Neural Network step by step.
## About the dataset:
#### We have a dataset of stock prices from 01/2012 to 12/2016 and we have to predict the stocks for 01/2017. We have two datasets for training and other for testing
## Feature Scaling:
#### We are going to use Normalization method when working with RNN and a Sigmiod function in the output layer
## 60 time stamps:
#### In this dataset we need 60 time stamps so that we will predict the 61 th price so we require 60 last results from train so that we can predict the test 1st result
## RNN:
#### We used four of LSTM layers along with for the last layer return sequence is false as we dont require futher storing of the data and 100 units of data was stored in each layer of LSTM
## Results
#### We got a loss of **0.0011** at 100 epoch which tells that our model is good in predicting the stock prices. 