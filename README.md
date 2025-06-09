# Litecoin Price Forecasting with Time Series Regression

This project applies time series regression techniques to forecast the daily closing price of Litecoin (LTC), one of the leading cryptocurrencies.

## 📘 Project Summary

- Cleaned and prepared historical LTC price data (2013–2025)
- Engineered lag-based and rolling statistical features
- Explored the data with visualizations and correlation analysis
- Applied and compared multiple regression models:
  - LassoLarsIC (tuned using AIC/BIC)
  - Huber Regressor
  - Gradient Boosting Regressor
- Evaluated performance using MSE, MAE, and R²
- Generated business recommendations based on model outputs

## 📊 Key Result

- **Best model**: LassoLarsIC (tuned)  
- **R² (Test set)**: 0.9897  
- **Application**: Real-time LTC price prediction and crypto trading support

## 🚀 Tools & Libraries

- Python (Pandas, NumPy, scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook

## 📁 Files

- `FDA_Assignment_Litecoin.ipynb` – Full notebook with data prep, EDA, modeling, and results

## 📌 Author

*Muhammad Fauzan* – MSc Data Analytics Student
