**Machine learning for nowcasting wind speed - Dr. Guo Environmental Engineering Lab**

Using data of wind gust events extracted from ASOS one-minute weather data. 
Predictors include temperature, pressure, past wind speed and past wind direction. 
Additional timeseries features are hour and month to capture daily trends and seasonality. 
Fit baseline, linear, and simple dense models and LSTM models of various complexities, some of which were far better than others. 
Overall, the wind speed minute to minute seems to be far too erratic to be able to predict reliably, though the models are usually able to capture general trends.
