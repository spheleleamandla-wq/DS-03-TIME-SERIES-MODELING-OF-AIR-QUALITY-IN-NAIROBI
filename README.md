# DS-03-TIME-SERIES-MODELING-OF-AIR-QUALITY-IN-NAIROBI
Time series modeling of Nairobi air quality (PM2.5/AQI) using ARIMA, SARIMA &amp; Prophet. EDA, stationarity testing, and forecasting for public health insights.


## Overview
Time series analysis and forecasting of air quality in Nairobi to predict PM2.5 and AQI levels for public health planning.

## Problem
Forecast future air quality levels in Nairobi using historical time series data to help identify pollution trends and high-risk periods.

## Dataset
Air quality data for Nairobi with timestamp, PM2.5, PM10, AQI, temperature, humidity. Daily/hourly records. Checked for missing values and outliers.

## Steps
1. EDA: Time plots, seasonal decomposition, trend and seasonality analysis for Nairobi pollution patterns.
2. Stationarity: ADF test, differencing and log transformation to make series stationary.
3. Modeling: ARIMA, SARIMA for seasonality, Prophet for trend and holidays, baseline Naive model.
4. Evaluation: Train/test split by time, evaluated with MAE, RMSE, and MAPE. Residual diagnostics.

## Results
SARIMA captured seasonal patterns best with lowest RMSE. Forecast shows pollution peaks during dry seasons and traffic hours. Model can predict 30 days ahead.

## Tech Stack
Python, Pandas, Matplotlib, Statsmodels (ARIMA/SARIMA), Prophet, Scikit-learn

## How to Run
pip install pandas statsmodels prophet matplotlib
jupyter notebook DS_03_Air_Quality_Nairobi.ipynb

Author: Sphelele Nxumalo | Data Science Lab 2026