# Time Series Forecasting with Machine Learning (Python)

A simple Time Series Forecasting project in Python using Machine Learning. It transforms a univariate time series into a supervised learning problem and applies Linear Regression to predict future values based on historical lag features. The project includes data preparation, model training, prediction, and visualization.


This project demonstrates a simple Time Series Forecasting approach using traditional Machine Learning. We use **Linear Regression** to predict future values based on lagged historical data.

---

## 📌 Objective

Forecast future values of a time series using a supervised learning technique — transforming the problem into a regression task using lag features.

---

## 🧠 Model Used

- **Linear Regression** from `scikit-learn`

We use lag features as inputs to predict the current value of the series. For example:
- Inputs: `Value(t-1)`, `Value(t-2)`, ..., `Value(t-5)`
- Target: `Value(t)`

---

## 📦 Libraries Required

Install the required packages using pip:

pip install pandas numpy matplotlib scikit-learn

