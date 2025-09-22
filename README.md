# Time Series Forecasting with ARIMA (Short Sample)

This project contains a short (≈1 year) sample stock dataset and a Jupyter notebook demonstrating ARIMA forecasting.

## Contents
- `time_series_arima.ipynb` - notebook with steps: load data, decomposition, ADF test, ACF/PACF, ARIMA fit and forecast
- `data/apple_stock_short.csv` - short sample of AAPL-like daily closing prices (business days)
- `screenshots/` - plots generated from the notebook

## How to run
1. Create environment and install requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Open the notebook and run cells:
   ```bash
   jupyter notebook time_series_arima.ipynb
   ```

Notes: This dataset is synthetic but resembles a short real stock series for demo purposes. For real forecasting try using real price data from Yahoo Finance (`yfinance`) or other sources.
