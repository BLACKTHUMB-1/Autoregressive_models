# Autoregressive_models

Handle the missing values and imputed the missing values.
Additive Seasonal Decomposition
Multiplicative Seasonal Decomposition
Auto Regression models of forecasting a time series data. 
In the Auto Regression methods, you will be using the correlation between the past values of the time-series data, just like how you used correlation while studying linear regression. 
In the AR set of methods, you are still using the past values of the time-series, but you are also considering the correlation of those past values with the actual/current values.

Many a time it happens that the performance of both the smoothing methods and AR set of methods is the same (i.e. the RMSE/MAPE values will nearly be the same), but the model-building approach for forecasting in both of these paradigms of time series is quite different. 
In this module, we will again look at the airline-passenger example and build all the AR set of models on it. 
We will again compare their MAPE and RMSE values and will in-turn now compare their performance to the previously built smoothing methods as well.

Topics Covered in the repository:

Stationarity
Stationarity test
Non-stationarity to stationarity
Autocorrelation function 
Partial autocorrelation function
Auto Regressive model
Moving average model
Auto-Regressive Moving Average (ARMA)
Auto-Regressive Integrated Moving Average (ARIMA)
Seasonal Auto-Regressive Integrated Moving Average (SARIMA)
Seasonal Auto-Regressive Integrated Moving Average with Exogenous variable (SARIMAX)
RMSE and MAPE
