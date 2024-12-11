# GARCH
# Volatility Prediction using GARCH Models

This project demonstrates the use of GARCH (Generalized Autoregressive Conditional Heteroskedasticity) models to predict stock return volatility over time. The dataset used is historical monthly stock prices fetched using Yahoo Finance. The project also includes rolling forecasts for volatility and future predictions using the ARCH package in Python.

## Features
- Fetch historical stock price data using Yahoo Finance.
- Calculate percentage returns for the stock.
- Visualize return series and autocorrelation of squared returns.
- Fit a GARCH model to predict return volatility.
- Perform rolling forecasts for one-step-ahead volatility predictions.
- Predict volatility for the next 7 months.

  # Libraries
  - `pandas`: Data manipulation.
  - `numpy`: Numerical operations.
  - `yfinance`: Fetching financial data.
  - `matplotlib`: Visualization.
  - `statsmodels`: Time series plots.
  - `arch`: Fitting GARCH models.
  - `sklearn`: Model evaluation metrics.
  - `dateutil`: Handling date arithmetic.

- **Plots**:
  - Percentage return series.
  - Partial autocorrelation plot of squared returns.
  - Rolling forecast of volatility.
  - Predicted volatility for the next 7 months.
- **Metrics**:
  - Mean Squared Error (MSE) and Mean Absolute Error (MAE) for rolling forecasts.


## Future Improvements
- Support for other GARCH model variants (e.g., EGARCH, TGARCH).
- Include additional financial metrics for analysis.
- Enhance visualization with interactive plots using Plotly.

### Contributions
Feel free to fork the repository and submit pull requests for enhancements or bug fixes!

