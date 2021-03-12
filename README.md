# Time_Series_Project

Hello, my name is Sophie Wang and I'm receiving a Master's Degree in Data Science at University of San Francisco. This is the project I completed for the Time Series Modeling course.

## Project description 
The Zillow dataset recorded Feb 2008 - Dec 2015 monthly median sold price for housing in California, Feb 2018 - Dec 2016 monthly median mortgage rate and Feb 2008 - Dec 2016 monthly unemployment rate. The goal is to predict the monthly median sold price for Jan-Dec 2016. Features in the datasets are:Date,MedianSoldPrice,MedianMortageRate,UnemploymentRate.

## Modeling methods:
##### 1: Univariate models 
         a) ARIMA
         b) SARIMA
         c) ETS
         d) Facebook Prophet
         
##### 2: Multivariate models
         a) VAR
         b) SARIMAX
         c) LSTM
 

Our winner model is univariate Prophet using RMSE and MAPE as the evaluation metrics on the test set (2016 data). Please find more detailed discussions in the project write-up and jupyter notebook in this repository.

A summary of advantages and disadvantages of different modeling approaches is also attached in this repository.
         




