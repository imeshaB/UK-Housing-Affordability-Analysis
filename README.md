# 🏠 UK Housing Affordability Analysis & Forecasting

## 📌 Project Overview
This project analyses **housing affordability trends across England and Wales (2002–2024)** using data from the Office for National Statistics (ONS).  

It combines **time-series forecasting, regional modelling, and validation techniques** to understand affordability dynamics and predict future trends.

---

## 📊 Dataset
- Source: ONS Housing Affordability & Earnings Data  
- Coverage: **318 Local Authorities, 10 Regions**  
- Time period: **2002 – 2024**  

### Key Variables
- Median House Price  
- Median Earnings  
- Affordability Ratio (Price-to-Earnings)

---

## 🧠 Methodology

### 🔹 Data Processing
- Merged multiple ONS datasets  
- Converted wide → long format  
- Cleaned missing values  
- Generated final modelling dataset  

---

### 🔹 Time-Series Forecasting (UK Level)

Models evaluated:
- Naive Baseline  
- Rolling Mean (2-year & 3-year)  
- Drift Model  
- Linear Trend Regression  
- ARIMA (1,1,1)  
- Holt Exponential Smoothing  

---

### 🔹 Model Comparison

| Model | RMSE |
|------|------|
| **Rolling Mean (2)** | **0.51 ✅ Best** |
| Naive Baseline | 0.54 |
| Linear Trend | 0.58 |
| ARIMA | 0.61 |

👉 **Best Model Selected: Rolling Mean (2)**

---

### 🔹 Regional Forecasting & Validation

Approach:
- Rolling Mean forecasting per region  
- Holdout validation (2020–2024)  
- Walk-forward validation  

---

## 🔁 Model Validation Results

### 📊 Holdout Performance
- Best region: **North East (RMSE ≈ 0.32)**  
- Worst region: **London (RMSE ≈ 0.98)**  

---

### 🔄 Walk-Forward Validation
- Average RMSE ≈ **0.54**  
- Model shows:
  - ✔ Stable performance  
  - ✔ Good generalisation  
  - ✔ No overfitting  

---

## 🔍 Key Insights

### 📈 National Trend
- Affordability increased from **~5.1 (2002)** → **8.05 (2024)**  
- Forecast: **~8.43 by 2029**  

👉 Indicates **worsening affordability**, but with slowing growth.

---

### 🌍 Regional Differences

| Region | Insight |
|------|--------|
| North East | Most stable, highly predictable |
| Yorkshire | Strong model performance |
| London | Highly volatile, hardest to predict |

👉 London behaves differently due to **market complexity and price volatility**

---

### 🤖 Model Insight
- Simple models outperformed complex models  
- Random Forest and ARIMA did **not outperform baseline**  
- Indicates a **smooth, trend-driven time series**

---

## 🔮 Forecast (2025–2029)

| Year | Forecast Affordability |
|------|----------------------|
| 2025 | ~8.20 |
| 2026 | ~8.25 |
| 2027 | ~8.30 |
| 2028 | ~8.35 |
| 2029 | ~8.43 |

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Statsmodels)  
- Time-series forecasting  
- Machine learning (Random Forest)  
- Tableau (interactive dashboard – coming soon)
- Google Colab  
