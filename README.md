# 7PAM2002-0509-2023---Data-Science-Project
# Bitcoin Price Prediction

## Overview

This project aims to predict Bitcoin prices using advanced machine learning models and statistical techniques. Given the volatile nature of cryptocurrencies, accurately predicting Bitcoin prices poses significant challenges. This project explores the effectiveness of various models to forecast Bitcoin's future values using historical data.

## Project Objectives

- Analyze and preprocess historical Bitcoin price data to ensure model accuracy.
- Implement and evaluate the performance of multiple predictive models:
  - Long Short-Term Memory (LSTM)
  - AutoRegressive Integrated Moving Average (ARIMA)
  - Bayesian Ridge Regression
  - Prophet
- Compare the predicted model accuracy against actual prices using Mean Absolute Error (MAE).
- Identify the most reliable model for Bitcoin price prediction and discuss the limitations of each model.

## Dataset

The dataset used for this study was obtained from Kaggle. It includes Bitcoin price data from 2017 to 2022, with several years of daily fluctuations in Bitcoin prices. The data is provided in CSV format and is used to train and evaluate the predictive models.

## Methodology

1. **Data Preprocessing**:
   - Handling missing data using interpolation techniques.
   - Normalizing the data using Min-Max scaling to ensure consistency.
   - Splitting the data into training and testing sets to validate model performance.

2. **Model Implementation**:
   - **LSTM (Long Short-Term Memory)**: Captures temporal dependencies and non-linear relationships in sequential data.
   - **ARIMA (AutoRegressive Integrated Moving Average)**: Traditional statistical model suitable for time series data with trends and seasonality.
   - **Bayesian Ridge Regression**: Provides robust predictions in the presence of multicollinearity.
   - **Prophet**: A model developed by Facebook designed to handle time series data with trends and seasonality, even in the presence of missing data.

3. **Model Training and Validation**:
   - Each model is trained on historical data and evaluated on unseen test data.
   - The performance of the models is compared using the Mean Absolute Error (MAE) metric.

## Results

- **ARIMA**: Achieved the lowest MAE, making it the most effective model for predicting Bitcoin prices in this study.
- **LSTM**: Showed promise in capturing complex patterns but had a higher MAE compared to ARIMA.
- **Bayesian Ridge Regression and Prophet**: Performed less effectively, indicating limitations in handling the volatility and non-linearity of Bitcoin prices.

## Future Work

Future improvements could include:
- Incorporating external factors to enhance model predictions.
- Exploring hybrid models combining multiple techniques for better accuracy.
- Real-time prediction capabilities using optimized deep learning models.

colab link : https://colab.research.google.com/drive/1-0uk63BdkyjOpAEg_moyXbZZUGPxQDdQ?usp=sharing
