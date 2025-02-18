# 📊 Stock Market Volatility Modeling

This repository contains a **Jupyter Notebook** that analyzes **stock market volatility** using various machine learning and deep learning models. The dataset includes **historical stock prices** and **VIX Volatility Index data**, processed with feature engineering and predictive modeling.


## **📊 Project Overview**
The goal of this project is to **predict stock market volatility** using various modeling techniques and evaluate their effectiveness.

### ✅ **Key Features**
- **Data Collection**: Fetches stock price and volatility index (VIX) data using `yfinance`.
- **Feature Engineering**:
  - Log Returns 📉
  - Moving Averages (SMA 20, SMA 50)
  - Relative Strength Index (RSI)
  - Rolling Standard Deviation & Volatility Indicators
- **Predictive Models**:
  - 📊 **Linear Regression** - Traditional statistical modeling.
  - 🤖 **Support Vector Regression (SVR)** - Machine learning-based approach.
  - 🔥 **Long Short-Term Memory (LSTM)** - Deep learning time-series forecasting.
  - 📈 **GARCH Model** - A statistical approach for volatility modeling.
- **Model Evaluation**:
  - Mean Squared Error (MSE)
  - R-Squared Score (R²)
  - Actual vs Predicted Volatility Plots


## **🛠 Installation**
To install the required dependencies, run:

```bash
pip install -r requirements.txt
```

- If using Google Colab, install the necessary packages inside the notebook:

```bash
!pip install yfinance pandas numpy arch scikit-learn matplotlib seaborn ta tensorflow



