# Analysis-of-Gravitational-Wave-data
In this project we did analysis on the Gravitational Wave data by using two models. The Arima Model (Auto Regressive Integrated Moving Average) and the ARM model(Auto Regressive Model).

# Data information: 
Gravitational wave strain for GW150914_R1 for L1, 
This file has 4096 samples per second, 
Starting GPS 1126259447 duration 32.

# ARIMA Model:
ARIMA, short for ‘Auto Regressive Integrated Moving Average’ is actually a class of models that ‘explains’ a given time series based on its own past values, that is, its own lags and the lagged forecast errors, so that equation can be used to forecast future values.
Any ‘non-seasonal’ time series that exhibits patterns and is not a random white noise can be modeled with ARIMA models.
An ARIMA model is characterized by 3 terms: p, d, q
where,
p is the order of the AR term
q is the order of the MA term
d is the number of differencing required to make the time series stationary
If a time series, has seasonal patterns, then you need to add seasonal terms and it becomes SARIMA, short for ‘Seasonal ARIMA’. More on that once we finish ARIMA.

# ARM Model:
Auto Regressive Model: A regression model, such as linear regression, models an output value based on a linear combination of input values. 
(yhat = b0 + b1*X1), Where 
yhat is the prediction, 
b0 and b1 are coefficients found by optimizing the model on training data, and 
X is an input value. 
This technique can be used on time series where input variables are taken as observations at previous time steps, called lag variables.
