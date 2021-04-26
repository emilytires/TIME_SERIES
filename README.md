# TIME_SERIES
A time series is a series of data points over time. Time series forecasting is the use of a model to predict future values based on previously observed values.

TIME SERIES BASIC CONCEPTS

  Stationary : A stationary time series is one whose properties do not depend on the time at which the series is observed. Thus, time series with trends, or with seasonality, are not stationary.
   
  Trend : Trend is the increasing or decreasing values in the long time in a series.
  
  Seasonality : It is the repeating short-term cycles in the series.

  Random Noise : It is random variation in the series. This is the unexplained variation that solely happens by chance.
  
 
 TIME SERIES ANALYSIS
 
 1. Exponential Smoothing Methods

     1.1 Moving Average, Weighted Average : For a simple moving average, the formula is the sum of the data points over a given period divided by the number of periods. Weighted moving averages assign a heavier weighting to more current data points since they are more relevant than data points in the distant past.

     1.2 Single Exponential Smoothing (a) only if the time series is stationary.
   
     1.3 Double Exponential Smoothing (a, b) time series is not stationary but it has trend.
   
     1.4 Triple Exponential Smoothing (a, b, g) time series is not stationary but it has trend and seasonality. Holt Winters.


 2. Statistical & Econometric Methods

     2.1 AR(p) - AutoRegression Model , MA(q) - Moving Average Model , ARMA(p, q) - Autoregressive Moving Average Model is similar to SES.
  
     2.2 ARIMA(p, d, q) - AutoRegressive  Integrated Moving Average is similar to DES.
  
     2.3 SARIMA (p, d, q) (P, D, Q)m - Seasonal AutoRegressive  Integrated Moving Average is similar to TES.
  
 3. Machine Learning for Time Series Forecasting

     3.1 LightGBM
 
