# 🏠 UK Housing Affordability Analysis

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-lightgrey)
![Time-Series](https://img.shields.io/badge/Time%20Series-Forecasting-orange)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

🚀 End-to-end data analytics project analyzing UK housing affordability trends using ONS data, time-series forecasting, and Tableau dashboards.

---

## Problem Statement

Housing affordability in the UK has worsened significantly over the past two decades, with **house prices rising faster than earnings**, creating economic and social challenges.  

This project aims to:

- Analyse historical trends (2002–2024)  
- Identify **regional disparities**  
- Forecast future affordability (2025–2029)  
- Deliver actionable insights for **policy, investment, and planning decisions**

---

## Project Goal

Turn complex housing data into **clear insights and forecasts** that show:

- How affordability is changing over time  
- Which regions are most/least affected  
- How future trends are likely to evolve

---

## Key Insights

- UK affordability worsened from **5.12 (2002)** → **8.05 (2024)**  
- **House prices consistently outpace earnings**, indicating structural pressure  
- **London & South East** are the least affordable regions; **North East** is most affordable  
- Forecast shows continued pressure with UK ratio reaching **8.43 by 2029**  
- Regional analysis reveals **hidden disparities** not visible in aggregate data

---

## Tableau Dashboard Visuals

### 📈 UK Affordability Trend

![UK Trend - Tableau](https://raw.githubusercontent.com/imeshaB/UK-Housing-Affordability-Analysis/master/Outputs/Figures/UK%20Trend%20(Dasboard%20Worksheet).png)

📊 Built in Tableau to simulate real-world business dashboards

---

### 🌍 Regional Comparison

![Regional Comparison - Tableau](https://raw.githubusercontent.com/imeshaB/UK-Housing-Affordability-Analysis/master/Outputs/Figures/Regional%20Comaprison%20(Dasboard%20Worksheet).png)

📊 Shows strong regional disparities

---

### 📊 Model Validation (Actual vs Predicted)

![Validation Chart - Tableau](https://raw.githubusercontent.com/imeshaB/UK-Housing-Affordability-Analysis/master/Outputs/Figures/Validation%20ResultsActual%20vs%20Predicted%20Chart%20(Dasboard%20Worksheet).png)

📊 Confirms reliability of forecasting models

---

## Methodology

- **Data Cleaning & Integration**: Merged ONS, Land Registry, ASHE datasets  
- **Exploratory Data Analysis (EDA)**: Trends, regional comparisons, affordability gaps  
- **Affordability Ratio Calculation**: Price-to-income metrics  
- **Forecasting**: Rolling Mean, Naive, Linear Regression, ARIMA  
- **Validation**: Walk-forward validation + RMSE analysis  
- **Visualization**: Tableau dashboards and static charts  

---

## Forecasting Results

| Model | RMSE |
|-------|------|
| **Rolling Mean (Best)** | 0.51 |
| Naive | 0.54 |
| Linear Regression | 0.58 |
| ARIMA | 0.61 |

- **Rolling Mean** performed best due to strong historical trend stability  

---

## Business & Policy Impact

- Supports **housing policy evaluation**  
- Highlights **regions with critical affordability pressure**  
- Informs **investment & planning decisions**  
- Demonstrates **end-to-end analytical thinking**  

---

## Relevance to Roles

### 🏥 NHS / Public Sector

- Population-level analysis of housing inequality  
- Evidence-based policy insights  
- Supports resource allocation and service planning  

### 💼 Consulting

- Structured approach: Problem → Analysis → Insights → Forecast  
- Communicates actionable insights to stakeholders  
- Shows ability to **deliver client-ready dashboards**

### 📊 Data Analyst Roles

- Demonstrates data cleaning, validation, EDA  
- Shows forecasting and modelling expertise  
- Builds **reliable dashboards** for insight communication  

---

## Tech Stack

- Python (Pandas, NumPy, Statsmodels, Scikit-learn)  
- SQL (data handling & preparation)  
- Tableau (dashboard development)  
- Jupyter Notebook  

---

## Future Improvements

- Integrate rental & demographic datasets  
- Apply advanced forecasting models (Prophet, LSTM)  
- Build interactive dashboard deployment  
- Automate real-time data pipeline  

---

## Contact

- 📧 Email: imeshabandara@gmail.com  
- 💼 LinkedIn: [imeshabandara](https://www.linkedin.com/in/imeshabandara/)  

---

## ⭐ If you found this useful

Give this project a ⭐ — it helps visibility and supports my work!
