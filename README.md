# Time_series_forcasting1

In this notebook we will try to make a model which will predict/forecast the closing price of the Nifty50 index(India).
For this purpose we will we using time series modeling on the data from past few years which includes information like opening price,
closing price,high and low of the index on daily basis.

To make this model we will be using ARIMA model.
ARIMA stands for Auto Regressive Integrated Moving Averages. It takes three parameters namely p,d,q (a specific for each term included in AR-I-MA).
p means the number of previous values which will be used to regress the data.
d means the difference.
q means the number of previous errors in predicting.

The value of these parameters are non negative integers and different combination of these parameters give us different models. 

Together they make ARIMA(p,d,q) model.

This task is divided into different parts.
A. Considering and importing all the required libraries that will be needed .
B. Reading the data and making required changes in it.
C. Checking for stationarlity.
D. Splitting the data.
E. Trainig and Prediction.

Results and Inference:
The model was able to predict the increasing or decreasing trend in the stock index price but the prediction was not very accurate. This is obvious because the markets are 
asffected by many other features also and a simple model with a single feature could not predict the accurate results.
The results can be made accurate by using mulltiple featres(endogenous-for less time consuming model and both exogenous and endogenous-for good results but more time consuming) and using DNNs for training and predicting.

