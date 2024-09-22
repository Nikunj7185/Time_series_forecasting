# Time Series Forecasting Project

This project demonstrates various time series forecasting methods, including traditional statistical models, machine learning models, and deep learning approaches. The goal is to experiment with different models to predict future values based on historical data.

## Project Structure

- **data/**  
  Contains the CSV files used for the forecasting models.

- **00_Auto_regressor.ipynb**  
  Implements an automatic regressor for time series forecasting using basic models for quick predictions.

- **01_ARIMA.ipynb**  
  Demonstrates the use of the ARIMA model (AutoRegressive Integrated Moving Average), a popular statistical method for time series analysis and forecasting.

- **02_TSF_Using_ML(LR_&_RF).ipynb**  
  Explores time series forecasting using machine learning models such as Linear Regression (LR) and Random Forest (RF).

- **03_TSF_using_RNNs(LSTM).ipynb**  
  Implements Recurrent Neural Networks (RNNs) with Long Short-Term Memory (LSTM) layers for forecasting time series data, focusing on capturing complex patterns over time.

- **04_TSF_VAR.ipynb**  
  Demonstrates the use of Vector Auto-Regressor in forecastinf timeseries that might be dependent on each other. Also tells how to find if two time series even are dependent.

- **decomposition.ipynb**  
  Decomposes time series data into its components (trend, seasonality, and residuals) using `statsmodels` to better understand its structure.

- **README.md**  
  This file provides an overview of the project and instructions for running the notebooks.

- **requirements.txt**  
  Lists the required Python packages and libraries needed to run the notebooks in this project.
