# SARIMA-model

Seasonal Autoregressive Integrated Moving Average (SARIMA) is implemented for time series forecasting with univariate data containing trends and seasonality.

Autoregressive Integrated Moving Average (ARIMA) is one of the most widely used forecasting methods for univariate time series data forecasting. Although the method can handle data with a trend, it does not support time series with a seasonal component. An extension to ARIMA that supports the direct modeling of the seasonal component of the series is called SARIMA.

ARIMA supports both an autoregressive and moving average elements. The integrated element refers to differencing allowing the method to support time series data with a trend. A problem with ARIMA is that it does not support seasonal data. That is a time series with a repeating cycle.

SARIMA or Seasonal ARIMA, is an extension of ARIMA that explicitly supports univariate time series data with a seasonal component. It adds three new hyperparameters to specify the autoregression (AR), differencing (I) and moving average (MA) for the seasonal component of the series, as well as an additional parameter for the period of the seasonality.
