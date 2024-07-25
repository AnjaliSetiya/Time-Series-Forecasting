**Data**
Quarterly Series : 2 | Time Steps:33

Monthly Series : 3 | Time Steps:204

**Tasks:**
Appropriate charts to understand the characteristics of the time series.
Forecast of each of the 12 time steps for each series

**Assumption:** The solutions are based on the assumption that the two quarterly series and the three monthly series areunivariateinnature based on the problem statement.
Exploratory Data Analysis

**Modelling**

Time Series Plotting:
• Purpose: Visual inspection of data to identify trends, seasonality, and irregular components.
• Why: Initial step to understand data behavior over time.

Rolling Statistics:
•Purpose: To observe the moving average and moving variance, helping to spot trends and volatility changes.
•Why: Helps in a preliminary check for stationarity.

Decomposition of Series:
•Purpose: Separation of data into trend, seasonal, and residual components.
•Why: To understand underlying patterns and to aid in handling the stationarity in the data.

Stationarity Testing with ADF:
•Purpose: Applying Augmented Dickey-Fuller test to formally testfor the presence of a unit root.(non-stationarity)
•Why: Confirming stationarity is crucial before applying certainstatistical models.

ACF and PACF Plots:

•Purpose: To identify the autocorrelation in the data which helps in selecting ARIMA model parameters.
•Why: These plots determine the order of the AR and MA components in ARIMA models.

Parameter Selection with Auto ARIMA:

• Purpose: Automated search for the best ARIMA model parameters based on the data.

• Why: Optimizes model selection process by finding the best fit with minimal AIC.

SARIMA Model Predictions:
•Purpose: Applying Seasonal ARIMA models to forecast future data points with seasonality adjustments.
•Why: SARIMA accounts for both seasonality and trends, providing more accurate forecasts.

Prophet
•Purpose: Prophet is compared with SARMIA method for quarterly data
•Why: The stark decrease in the series values in Quartely series around 2020 calls for mapping these peculiar irregularities.
