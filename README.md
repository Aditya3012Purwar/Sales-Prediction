# Sales-Prediction

This repository contains Python scripts for analyzing and forecasting time series data. The analysis is based on a dataset of monthly sales data, which is evaluated for stationarity and then forecasted using ARIMA and SARIMAX models.

![image](https://github.com/Aditya3012Purwar/Sales-Prediction/assets/103439955/3b09a833-6b39-4dcc-a60d-2d24a1319305)

### Prerequisites

- Python 3.10
- Libraries:
  - seaborn
  - numpy
  - pandas
  - matplotlib
  - statsmodels

### Data

The data is expected to be a CSV file named `month sales.csv`, containing monthly sales data. Make sure to place this file in the appropriate directory or update the file path in the code accordingly.

### Execution

The script performs the following tasks:

- Loads the monthly sales data from a CSV file
- Converts the month column to datetime format and sets it as the index
- Plots the sales data
- Conducts the Augmented Dickey-Fuller test to check for stationarity
- Differentiates the data to achieve stationarity, if necessary
- Plots the autocorrelation and partial autocorrelation plots
- Fits ARIMA and SARIMAX models to the data
- Predicts future sales and plots the forecasts

To execute the script, simply run the provided Python file in a suitable environment, such as Jupyter Notebook or directly on a Python interpreter.

### Output

The script will generate plots visualizing the original sales data, the differentiated data to achieve stationarity, the autocorrelation and partial autocorrelation plots, and the forecasted sales data using ARIMA and SARIMAX models.

![image](https://github.com/Aditya3012Purwar/Sales-Prediction/assets/103439955/7a2c141e-d6f2-4ae6-b13c-f62d4466ac85)
