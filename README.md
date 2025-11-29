# 📈 Stock Price Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn%20%2F%20TensorFlow-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📖 Overview
This project is a Machine Learning application designed to predict future stock prices based on historical data. By utilizing time-series analysis and algorithms like **Long Short-Term Memory (LSTM)** or **Linear Regression**, the model analyzes patterns in past stock trends to forecast future values.

This tool is useful for traders, financial analysts, and data science enthusiasts looking to understand market trends programmatically.

## ✨ Features
* **Data Collection:** Automated data fetching using Yahoo Finance (`yfinance`) API.
* **Data Preprocessing:** Handling missing values, scaling data (MinMax/Standard Scaler), and sequence generation.
* **Visualization:** Interactive charts comparing **Actual vs. Predicted** prices.
* **Model Performance:** Evaluation metrics including RMSE (Root Mean Squared Error) and MAPE (Mean Absolute Percentage Error).
* **Customizable:** Easily switch between different stock tickers (e.g., AAPL, GOOGL, TSLA).

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:**
    * `Pandas` & `NumPy` (Data Manipulation)
    * `Matplotlib` & `Seaborn` (Visualization)
    * `Scikit-Learn` (Data Splitting & Linear Models)
    * `Keras` / `TensorFlow` (For LSTM/Deep Learning models)
    * `Yfinance` (Stock Data API)

## 📊 Project Architecture
1.  **Data Acquisition:** Fetching historical stock data (Open, High, Low, Close, Volume).
2.  **Exploratory Data Analysis (EDA):** Visualizing moving averages and volatility.
3.  **Feature Engineering:** Creating technical indicators (e.g., RSI, MACD).
4.  **Model Training:** Training the ML/DL model on training data.
5.  **Prediction & Evaluation:** Testing on unseen data and plotting results.
