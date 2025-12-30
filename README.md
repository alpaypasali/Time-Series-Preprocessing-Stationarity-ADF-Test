# 📈 Time Series Forecasting with Exponential Smoothing

This project presents an **end-to-end time series analysis and forecasting workflow** using classical statistical methods.  
The study focuses on understanding the structure of the time series and applying **Exponential Smoothing techniques** to produce accurate short-term forecasts.

---

## 🚀 Project Overview

The main goals of this project are:

- Analyze the time series structure (trend & seasonality)
- Test stationarity using statistical methods
- Apply smoothing techniques to reduce noise
- Build and evaluate multiple Exponential Smoothing models
- Optimize model parameters for improved forecasting accuracy

---

## 📦 Libraries & Tools

The following Python libraries are used:

- **pandas**, **numpy** – data manipulation  
- **matplotlib**, **seaborn** – visualization  
- **statsmodels** – time series analysis & forecasting  
- **scikit-learn** – evaluation metrics  

---

## 🔧 Data Preprocessing

- Time series is **resampled to monthly frequency**
- Missing values are handled using **time-based interpolation**
- Data is split into **train and test sets** using a time-aware approach to prevent data leakage

---

## 🧪 Stationarity Analysis

Stationarity is tested using the **Augmented Dickey-Fuller (ADF) Test**.

- **H₀:** The time series is non-stationary  
- **H₁:** The time series is stationary  

Based on the p-value, the stationarity assumption is statistically validated before modeling.

---

## 📉 Time Series Decomposition

The series is decomposed using an **additive model** into:

- **Observed**
- **Trend**
- **Seasonal**
- **Residual**

This step helps clearly identify underlying patterns and supports model selection.

---

## 🧪 Smoothing & Forecasting Models

Multiple Exponential Smoothing models are implemented and compared:

### 🔹 Simple Exponential Smoothing (SES)
- Captures level only
- Suitable for series without trend or seasonality

### 🔹 Double Exponential Smoothing (Holt’s Method)
- Captures level and trend
- Suitable for trending time series

### 🔹 Triple Exponential Smoothing (Holt–Winters)
- Captures level, trend, and seasonality
- Applied with additive components

---

## ⚙️ Model Optimization

Smoothing parameters are manually tuned to improve forecasting accuracy.  
The optimized model is evaluated on the test set.

---

## 📊 Results

- The optimized **Exponential Smoothing model** successfully captures both **trend and seasonality**
- Predictions closely align with the test data
- Achieved a **low MAE of 0.59**, indicating strong forecasting performance

This confirms the effectiveness of smoothing-based models for short-term time series forecasting.

---

## 🎯 Conclusion

This project demonstrates that:

- Proper **stationarity checks** are essential before modeling
- **Smoothing techniques** significantly improve trend visibility
- Optimized **Exponential Smoothing models** can deliver accurate and interpretable forecasts

The workflow provides a solid foundation for classical time series forecasting problems.

---

## 📌 Future Improvements

- Add ARIMA / SARIMA model comparisons
- Perform automatic hyperparameter optimization
- Extend evaluation with additional error metrics
- Apply the workflow to different real-world datasets

---



📎 Kaggle: https://www.kaggle.com/alpaypasali  
📎 GitHub: https://github.com/alpaypasali
