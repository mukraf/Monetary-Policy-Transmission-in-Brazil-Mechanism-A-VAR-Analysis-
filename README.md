# Monetary-Policy-Transmission-in-Brazil-Mechanism-A-VAR-Analysis-

The objective of this examination is to see if monetary policy transmits to the Brazilian economy through our estimated VAR model. For instance how will an increase in the Selic rate affect the economy? And how far can our model predict this? We estimate a Vector Autoregression (VAR) using Brazilian monthly data from March of 2004 to June of 2026. Using IBC-Br for economic activity, IPCA for inflation, Selic for interest rate and FX depreciation for USD/Real exchange rate.

Throughout this analysis we perform many steps of a standard VAR model. Testing our data for unit roots, lag selection, checking residuals, testing for stability, granger causality tests and forecasting. All these results we compare to monetary theory. Using our knowledge of the Taylor Rule we should expect our central bank to increase rates when both growth and inflation increase. We expect our IS Curve to behave appropriately when our exchange rate decreases causing a drop in growth. The same can be said for the Phillips curve and exchange rate. We find a VAR model with 4 lags that includes the Selic rate in it's natural units. We get great residuals and stable forecasts with the most accurate out of sample forecast. 
Almost all our Impulse Responses act as expected from monetary policy.

As stated before there is a price puzzle in our model where prices are increased when rates are raised. After including Focus 12 month projected inflation rate and IC-Br a raw material index provided by the Banco Central do Brasil. Our price puzzle decreases by roughly half and is not significant. We can now expect prices to fall two years after a rate increase which aligns with monetary policy.

Using a moving window of our out of sample data we can measure the accuracy of our model. From June 2022 to June 2026 we produce 48 out of sample forecasts. Measuring MAE, RMSE and MAPE along with Theils U statistic. 

At the end of this analysis, we will produce a forecast for all variables from July 2026 to June of 2027. Expecting IPCA to come in at approximately 5.3% in 2026 which is higher than our target upper bound of 4.5%. We can also see our Selic rate decrease to around 12.75% by the end of 2026.


