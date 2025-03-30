# Time-Series-Analysis-of-Candy-Production
In this project, I analyzed the monthly U.S. candy production index data from January 1972 to August 2017 using time series techniques. The objective was to understand trends, seasonality, and develop accurate forecasting models.

Here’s what I did:

1. Data Exploration:

- Loaded and plotted the time series data.

- Identified a clear upward trend and strong seasonal patterns, especially around Halloween to Christmas.

2. Smoothing Techniques:

- Applied Simple Moving Average (SMA) and Exponential Moving Average (EMA) with different parameters to smooth the data and assess trends.

3. Decomposition:

- Used Classical Additive & Multiplicative Decomposition and STL decomposition to break the series into trend, seasonal, and residual components.

4. Autocorrelation Analysis:

- Analyzed ACF and PACF plots to assess stationarity and identify lags for potential models.

5. Model Training & Forecasting:

- Split the data into training and validation sets.

- Built and compared baseline models: Mean, Naive, Seasonal Naive, and Drift.

- Trained advanced models: Holt-Winters and ARIMA (via auto.arima).

6. Model Evaluation:

- Performed residual diagnostics using Ljung-Box tests and ACF plots.

- Compared models using MAPE, RMSE, and other accuracy metrics.

- Selected the Seasonal Naive Model as the final forecasting model due to its lowest MAPE (9.91).

7. Final Forecast:

- Used the selected model to forecast future candy production and visualized the results.
