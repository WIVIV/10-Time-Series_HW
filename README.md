## Time-Series Forecasting
#### Initial Time-Series Plotting
<p align="center">
<img src="Images/Initial_Time-Series.png">
</p>



#### Settle Price vs the Trend
<p align="center">
<img src="Images/Settle_Price_vs_Trend.png">
</p>

#### Settle Noise
<p align="center">
<img src="Images/Settle_Noise.png">
</p>

#### Forecasting Returns using an ARMA Model
<p align="center">
<img src="Images/ARMA.png">
</p>

5 Day Returns Forecast
<p align="center">
<img src="Images/5Day_Returns_Forecast.png">
</p>

#### Forecasting Returns using an ARMIA Model
<p align="center">
<img src="Images/ARIMA.png">
</p>

5 Day Returns Forecast
<p align="center">
<img src="Images/5Day_Futures_Price_Forecast.png">
</p>

#### Volatility Forecasting with GARCH
<p align="center">
<img src="Images/GARCH.png">
</p>

Final Forecast
<p align="center">
<img src="Images/Final_Forecast.png">
</p>

1. Based on your time series analysis, would you buy the yen now?
* Yes there looks to be some short term buying opportunities as indicated by the ARMA and ARIMA models. 

2. Is the risk of the yen expected to increase or decrease?
The GARCH model forecasts that the risk of the Yen will increase in the near term. 

3. Based on the model evaluation, would you feel confident in using these models for trading?

* As the ARMA and ARIMA models are not good fits (P values >0.05), I would look to refine the models more before trading.  



### Linear Regression Forecasting
First 20 predictions vs the true values
<p align="center">
<img src="Images/20_predictions_vs_true_values.png">
</p>

Does this model perform better or worse on out-of-sample data compared to in-sample data?

* Out-of-Sample Root Mean Squared Error (RMSE): 0.4151933603075715
* In-sample Root Mean Squared Error (RMSE): 0.5657562717010388

As the Out-of-Sample Root Mean Squared Error is the lowest, the models performs best Out-of-Sample.

