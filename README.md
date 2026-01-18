# 🔥 Natural Gas Price Forecasting 📈

This project focuses on **analyzing and forecasting natural gas prices** using classical time series methods.  
It demonstrates how to **clean, preprocess, interpolate missing data, and forecast prices** using **ARIMA models** and **cubic spline interpolation** — techniques commonly used in energy markets and financial engineering.

---

## 🚀 Project Overview

The analysis covers:

- Loading and cleaning historical natural gas price data
- Handling missing observations using **cubic spline interpolation**
- Modeling and forecasting prices with **ARIMA (Autoregressive Integrated Moving Average)**
- Visualizing historical prices, interpolated series, and future forecasts

---

## 📊 Methodology

### 1️⃣ Data Loading & Cleaning
- Import historical natural gas price data
- Handle missing values and inconsistent timestamps
- Prepare data for time series modeling

### 2️⃣ Interpolation
- Apply **cubic spline interpolation** to:
  - Fill missing price values
  - Generate a smooth and continuous price curve
- Compare original vs interpolated data visually

### 3️⃣ Time Series Modeling
- Fit an **ARIMA model** to the processed price series
- Capture trend and autocorrelation structures
- Generate out-of-sample price forecasts

### 4️⃣ Visualization
- Historical price series
- Interpolated price curve
- Forecasted future prices with ARIMA

---

## 🔧 Tools & Libraries

- **Python**
- **pandas** – Data handling and preprocessing
- **SciPy (`interp1d`)** – Cubic spline interpolation
- **statsmodels (ARIMA)** – Time series forecasting
- **matplotlib** – Data visualization

---

## 📈 Key Insights

- Cubic spline interpolation effectively smooths missing data without distorting price trends
- Natural gas prices show strong temporal dependence
- ARIMA models capture short-term dynamics and provide reasonable forecasts
- The workflow mirrors real-world **energy price forecasting** pipelines

---

---

## 📌 Future Work

- Extend to **SARIMA** for seasonality
- Compare ARIMA with machine learning models (XGBoost, LSTM)
- Add exogenous variables (weather, storage levels, demand)
- Build a rolling forecast and backtesting framework

---

## 💡 Key Takeaway

This project demonstrates how classical time series methods can be applied to **commodity price forecasting**:

- Robust handling of missing data
- Interpretable statistical models
- Practical forecasting workflow for energy markets

---

## 👤 Author

**Dalitso Nthonyiwa**  
*MSc Financial Engineering | Energy Markets & Time Series Modeling*

---

⭐ If you find this project useful, feel free to star the repository!
