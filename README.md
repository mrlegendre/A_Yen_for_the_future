# Module_10_A-Yen_for_the_future

In this assignment, you will test the many time series tools that you have learned in order to predict future movements in the value of the Canadian dollar versus the Japanese yen.

## Return Forecasting: Time Series Analysis & Modelling with CAD-PHY Exchange rate data.

### Initial Time-Series Plotting
Question: Do you see any patterns, long-term and/or short? 

*A long term pattern shows that the JPY is getting stronger compared to CAD*

 ## Decomposition Using a Hodrick-Prescott Filter
  Using a Hodrick-Prescott Filter, decompose the exchange rate price into trend and noise.

## Exchange Rate Price vs. the Trend for 2015 to the present
![](/Images/Price_vs_Trend.png)

Question: Do you see any patterns, long-term and/or short?

*A long term pattern shows that the JPY is getting stronger compared to CAD*

## Settle Noise plot
![](/Images/noise.png)

## Forecasting the Exchange Rate Price using an ARIMA Model

Question: Based on the p-value, is the model a good fit?

*No, since p-values for this ARIMA model tend to be greater than 0.05*


![](/Images/ARIMA.png)

 Question: What does the model forecast will happen to the Japanese Yen in the near term?

 *In the near term the forecast shows that the Yen will get stronger compared to the CAD...it will increase in value.*

 ## Volatility Forecasting with GARCH
 ### 5 day forecast of volatility
![](/Images/GARCH.png)


 Question: What does the model forecast will happen to volatility in the near term?

 *The model forecast shows that the volatility will increase in the near term*

 ##  Regression Analysis: Seasonal Effects with Sklearn Linear Regression

 ### Predictions vs. True Values
 ![](/Images/LinearRegression.png)

  Question: Does this model perform better or worse on out-of-sample data as compared to in-sample data?

  *The model performs better for the out-of-sample data than the in-sample-data since the value of the out-of-sample RMSE is lower than the in-sample RMSE*

  #  Conclusions

  -Based on your time series analysis, would you buy the yen now?

*Based on this analysis I would buy now as the Yen will get stronger*

 
-Is the risk of the yen expected to increase or decrease?


*Based on the volatility (GARCH) model the risk will increase*

 
-Based on the model evaluation, would you feel confident in using these models for trading?

*Based on this model I would not feel confident in using it for trading due to the value of p>0.05 demonstrating that the model is not a good fit.*










