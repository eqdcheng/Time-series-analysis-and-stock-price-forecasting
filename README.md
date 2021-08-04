## My time series analysis and AMZN stock price forecasting

I learn and explore packages like Keras (tf), statsmodels (AMIRA), and Prophet. 

- First, I visualize the dataset, and then compare different models for price predictions. 
- ARIMA: The Autoregressive integrated moving average model preformed the best fit, using previous data to predict the next timestep. The picture on the right is ARIMA predicting AMZN prices. 
- LSTMs (RNN) are able to capture similar results as the statistical ARIMA model, using 2 years of training data to predict the next timestep. 
- Prophet is Facebook’s new timeseries analysis tool, and it has no train/test split. It takes all the data and predicts the next X number of days. 


*Tools used: Pandas, seaborn, numpy, matplotlib, tensorflow, keras,  lag_plot, statsmodels, sklearn*
