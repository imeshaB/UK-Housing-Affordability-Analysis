# 🏠 UK Housing Affordability Analysis

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-lightgrey)
![Time-Series](https://img.shields.io/badge/Time%20Series-Forecasting-orange)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

🚀 End-to-end analysis of 7,255 records across 318 UK local authorities — quantifying a 57% affordability deterioration (2002–2024) and forecasting regional trends to 2029 using validated time-series models (RMSE: 0.51).

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

![Dashboard](https://raw.githubusercontent.com/imeshaB/UK-Housing-Affordability-Analysis/master/Outputs/Figures/UK%20Housing%20Affordability%20Dashboard.png)


### 📈 UK Affordability Trend

![UK Trend - Tableau](https://raw.githubusercontent.com/imeshaB/UK-Housing-Affordability-Analysis/master/Outputs/Figures/UK%20Trend%20(Dashboard%20Worksheet).png)

📊 Built in Tableau to simulate real-world business dashboards

---

### 🌍 Regional Comparison

![Regional Comparison - Tableau](https://raw.githubusercontent.com/imeshaB/UK-Housing-Affordability-Analysis/master/Outputs/Figures/Regional%20Comaparison%20(Dashboard%20Worksheet).png)

📊 Shows strong regional disparities

---

### 📊 Model Validation (Actual vs Predicted)

![Validation Chart - Tableau](https://raw.githubusercontent.com/imeshaB/UK-Housing-Affordability-Analysis/master/Outputs/Figures/Validation%20Results%20Actual%20vs%20Predicted%20Chart%20(Dashboard%20Worksheet).png)

📊 Confirms reliability of forecasting models

---

## 🗂️ Data Sources

All data sourced from the **Office for National Statistics (ONS)** — publicly available.

| Dataset | Description | Link |
|---|---|---|
| Housing Purchase Affordability, Local Authority Areas, England and Wales | Affordability ratios at LA level across 318 authorities | [ONS ↗](https://www.ons.gov.uk/peoplepopulationandcommunity/housing/datasets/housingpurchaseaffordabilitylocalauthorityareasenglandandwales) |
| House Price to Residence-Based Earnings Ratio | Lower quartile and median price-to-earnings ratios by region | [ONS ↗](https://www.ons.gov.uk/peoplepopulationandcommunity/housing/datasets/ratioofhousepricetoresidencebasedearningslowerquartileandmedian) |

> Data covers **2002–2024** across **318 local authorities** and **10 English regions**.
> Downloaded as published ONS Excel files and processed into analytical format using Python.

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

## 🎯 Domain Applicability

| Sector | Relevance |
|---|---|
| 🏥 Public Sector / NHS | Housing inequality correlates with health deprivation — findings inform resource allocation and service planning |
| 💼 Consulting / Policy | Structured problem → analysis → forecast pipeline mirrors client engagement methodology |
| 🏦 Financial Services | Affordability ratio modelling transferable to mortgage risk, credit exposure, and regional investment strategy |
| 📊 Data & Analytics | End-to-end pipeline from raw ONS data to validated forecast to production Tableau dashboard |

---

## 🚀 Future Improvements

- Incorporate rental market and demographic datasets
- Apply advanced forecasting models (Prophet, LSTM)
- Extend spatial analysis to Local Authority District level with interactive mapping
- Build automated real-time ONS data pipeline
  
---

## 🛠️ Tech Stack

| Tool | Usage |
|---|---|
| Python (Pandas, NumPy) | **Data cleaning, transformation, and exploratory data analysis (EDA)**. Handles tabular data efficiently and performs calculations for time-series and affordability metrics. |
| Statsmodels / Scikit-learn | **Time-series modelling, forecasting, and validation**. Includes ARIMA, Exponential Smoothing, Linear Regression, Random Forest, and walk-forward evaluation. |
| Matplotlib / Seaborn | **Static visualisations** for trends, model outputs, and EDA charts to support analysis. |
| Google Colab | **Interactive analysis environment** for documenting code, workflow, and insights; ensures reproducibility and cloud-based execution. |
| Tableau (LOD Expressions) | **Dynamic calculated fields, FIXED LOD, and aggregations** to support complex KPI calculations. |
| Tableau (Dashboard Design) | **Interactive dashboards** with filters, parameter controls, and dynamic text for stakeholder-friendly insights. |

💡 **Workflow note:**  
1. **Python in Colab** → Data cleaning, EDA, and modelling  
2. **Colab Notebook** → Documenting analysis and visualising intermediate results  
3. **Tableau** → Creating interactive dashboards and KPIs to communicate findings effectively

---

## Contact

- 📧 Email: imeshabandara@gmail.com  
- 💼 LinkedIn: [imeshabandara](https://www.linkedin.com/in/imeshabandara/)  

---
