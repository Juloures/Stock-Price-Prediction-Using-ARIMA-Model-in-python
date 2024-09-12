# Stock Price Prediction Using ARIMA Model

## 1. Project Overview

This project predicts Walmart stock prices using an ARIMA model. The data is sourced from a CSV file and includes the adjusted closing prices of Walmart stocks over a period of time. The ARIMA model is trained using historical data, and its performance is evaluated using the Root Mean Squared Error (RMSE) metric.

## 2. Libraries Used

- **pandas**: Used for data manipulation and handling DataFrames.
- **numpy**: Library for numerical calculations.
- **matplotlib**: Used for plotting graphs and visualizing data.
- **gdown**: Downloads files from Google Drive.
- **ARIMA** (from `statsmodels.tsa.arima.model`): Function for time series modeling.
- **mean_squared_error** (from `sklearn.metrics`): Used to calculate the error between predicted and actual values.

## 3. Key Steps

### Importing Libraries:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import gdown
from statsmodels.tsa.arima.model import ARIMA
from sklearn.metrics import mean_squared_error
from math import sqrt
