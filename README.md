# Mutual-Funds-Forecasting-using-LSTM-and-NeuralProphet

# 📈 Mutual Fund Forecasting using LSTM and NeuralProphet  

## 📝 Project Description  
This project focuses on **forecasting Net Asset Value (NAV) prices of mutual funds** using two advanced time-series models: **LSTM (Long Short-Term Memory)** and **NeuralProphet**.  
The goal is to **compare the performance of both models** and analyze their effectiveness in predicting future NAV trends, helping investors and analysts make better decisions.  

The project uses **historical NAV data** of five mutual funds:  
- Nippon India  
- HDFC  
- Invesco  
- ICICI Prudential  
- ITI  

Models are trained, evaluated, and tested with metrics such as:  
- **Mean Absolute Error (MAE)**  
- **Mean Absolute Percentage Error (MAPE)**  

---

## ⚙️ Workflow  

### 1. Data Collection  
- Extracted **historical NAV prices** of selected mutual funds from **Yahoo Finance**.  
- Time range selected to ensure enough historical data for training.  

### 2. Data Preprocessing  
- Handled **missing values**.  
- **Normalized** NAV values for LSTM model.  
- Reshaped data into **sequences** for supervised learning (LSTM).  

### 3. Model Development  

#### 🔹 NeuralProphet  
- Configured with **seasonalities, lags, and forecast horizon**.  
- Captures **trend and seasonality** for time-series forecasting.  

#### 🔹 LSTM  
- Sequential model with **multiple LSTM layers**.  
- **Dropout** added for regularization.  
- **Dense layer** for final prediction.  

### 4. Training & Forecasting  
- Both models trained on historical data.  
- Forecasts generated for **90 days into the future**.  

### 5. Evaluation  
Models evaluated using:  
- **MAE (Mean Absolute Error)**  
- **MAPE (Mean Absolute Percentage Error)**  

Comparison made to check **which model performs better**.  

### 6. Visualization  
- Forecast results plotted with **Plotly** for interactive analysis.  
- Graphs show **actual NAV vs. predicted NAV**.  


