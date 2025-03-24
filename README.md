# NVDA Stock Price Prediction

### Group KDDM 6
### Members -
### Abdurrahman Mohamed Salim Ansari
### Sahil Ketkar
### Yash Shah

## Overview
This project aims to predict the stock price of NVIDIA (NVDA) for the period of March 24 to 28 using historical stock data. The prediction is carried out using the **Yahoo Finance API** to fetch stock data and the **ARIMA (AutoRegressive Integrated Moving Average)** model for time series forecasting.

## Features
- Fetches historical NVDA stock data using the `yfinance` API.
- Preprocesses the data for training.
- Implements the ARIMA model for predicting stock prices.
- Provides predictions for the next day and the next 5 days.
- Visualizes the actual vs. predicted stock prices.

## Installation
To run this project, ensure you have Python installed along with the necessary libraries:

```bash
pip install yfinance pandas numpy statsmodels matplotlib
```

## Usage
1. Clone this repository:
   ```bash
   git clone <repository_link>
   cd nvda-stock-prediction
   ```
2. Run the script:
   ```bash
   python NVDA_Stock_Predictor.ipynb
