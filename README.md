# Is-Stock-Price-Predictable-using-LSTM-


There are lot of false information in the net that showing people that LSTM or ML model can use to predict stock prices.
The objective of the project is to reject the idea that LSTM cannot be use to predict stock prices and why.

First Part:

First, i do is to use a standard programming step to predict the stock closing prices.
Then , i make use of visualisation tools like plotly to show the predicted price.
After which, i did a shifting of data from the predicted prices then visual the result to show that the predicted price are not really a prediction. Those result are just a follow the previous pirce movement.
Finally, i make the model to predict the price out of time-series data, the model show a extrapolation line. This show that the modol is predicting out of the data distribution.
Which this proved that the LSTM model is not able to predict stock prices.

Second Part:

Is more about stock data itself. 
Stock data might be a time-series data but it cannot be predicted as it is non-stationary and not normal distribution. 
To proof that stock data is non-stationay, i make use of KS-Test to prove stock data is not stationary
To proof that stock data is non-stationay, i make use of precentage change, log transfromation and other 2 stats library to show that stock data is not normal distribution. 
