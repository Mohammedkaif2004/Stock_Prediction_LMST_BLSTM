# 📈 Apple Stock Price Prediction using LSTM and Bidirectional LSTM

This project explores the use of LSTM and Bidirectional LSTM models for predicting Apple Inc. (AAPL) stock prices based on historical time series data. The goal is to understand how different time step sizes affect prediction performance.

## 🧠 Models Used

- **LSTM (Long Short-Term Memory)**
- **Bidirectional LSTM (BiLSTM)**

Each model was trained with 3 different time step sizes: **100**, **125**, and **150**.

---

## 📊 Performance Summary

### ✅ LSTM Results
| Time Step | RMSE (Test Data) |
|-----------|------------------|
| 100       | *Good*      |
| 125       | *Moderate*          |
| 150       | **Best (✔️)** - **RMSE: 7.21**

LSTM performed best with **150** time steps.

---

### ✅ BiLSTM Results
| Time Step | RMSE (Test Data) |
|-----------|------------------|
| 100       | *Moderate*       |
| 125       | **Best (✔️)** - **RMSE: 5.03** |
| 150       | **Worst** - RMSE: 39.53 😞

BiLSTM performed best with **125** time steps.

---

## 🛠️ Project Structure
Both models were trained using historical stock data to learn price patterns and trends. The trained models were also used to predict stock prices for the next 60 days. These future predictions are not guaranteed to be accurate but serve as a potential trend estimation for educational and research purposes.

---

## 📊 Features

- ✅ Preprocessing of historical stock price data (e.g., from Yahoo Finance)
- ✅ Implementation of LSTM and BiLSTM models for time series forecasting
- ✅ Evaluation of model performance using **MSE** (Mean Squared Error) and **RMSE** (Root Mean Squared Error)
- ✅ Comparative analysis of different time step inputs (100, 125, 150)
- ✅ Future stock price prediction for **60 days** using each trained model
- ✅ Visualization of:
  - Historical vs Predicted Prices
  - Future forecasted prices

> ⚠️ Note: The 60-day future forecasts are illustrative and intended for academic exploration only—not for financial decisions.


