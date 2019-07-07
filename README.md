# Time-series-analysis-and-prediction-of-Bitcoin

The main aim of this project is to analysis the closing prices of Bitcoin data using descriptive analysis, 
visualization, model specification, model fitting and selection, diagnostic checking,  and accurately predict 
the value of bitcoin for the next 10 days.

 Conclusion

The Analysis of the bitcoin data was very challenging. We were not able to satisfy all the model assumptions 
and criterias. Several Models were analysed and ARIMA(0,1,1) was found to be the best model based on residuals
and AIC values. The residuals from this model where used to model the GARCH series. Similar to the ARIMA series 
seberal GARCH models were analysed. Based on the residual analysis and AIC values the model chosen was 
**ARMA(0,1)+GARCH(2,1)** based on the scope of this subject.
\newline

Values                 | BEST MASE
-------------          | -------------
Over fitted values     | 7.5218
Over forecasts	       | 1.5255

