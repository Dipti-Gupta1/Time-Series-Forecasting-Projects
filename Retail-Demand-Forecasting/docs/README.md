# 🛒 Retail Demand Forecasting: A Comparative Study of Classical, Machine Learning & Deep Learning Models

### End-to-End Time Series Forecasting using Classical Time Series, Machine Learning & Deep Learning

![Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Forecasting](https://img.shields.io/badge/Domain-Time%20Series-success)
![License](https://img.shields.io/badge/License-GPL--3.0-green)

---

## 📖 Overview

Retail businesses rely heavily on accurate demand forecasting to optimize inventory, improve supply chain planning, and reduce operational costs.

This project develops an **end-to-end demand forecasting pipeline** capable of predicting **daily sales at the Store–Item level** using historical sales data and external business drivers.

Unlike a traditional forecasting notebook, this repository focuses on the **complete Data Science lifecycle**, from business understanding to deployment recommendations.

---

# 🎯 Business Problem

A retail supermarket chain operates multiple stores and manages thousands of products.

Customer demand fluctuates due to:

- Promotions
- Holidays
- Seasonality
- Store Characteristics
- Customer Transactions
- External Economic Factors

Poor demand forecasting can result in:

- Stock-outs
- Excess Inventory
- Inventory Holding Costs
- Lost Revenue
- Inefficient Supply Chain Planning

The objective is to build a forecasting solution that improves inventory planning and business decision-making.

---

# 🎯 Business Objectives

- Forecast future daily sales
- Improve inventory planning
- Reduce stock-outs and excess inventory
- Measure the impact of promotions on demand
- Analyze holiday effects on sales
- Compare Classical Time Series and Machine Learning models
- Identify key demand drivers

---

# 💼 Business Questions

| Category | Business Questions |
|-----------|--------------------|
| 📈 Demand Forecasting | Can future daily sales be accurately predicted?<br>Which forecasting model performs best? |
| 🎁 Promotion Analysis | How much do promotions increase product sales?<br>Do all product families respond similarly to promotions? |
| 🎉 Holiday Analysis | How do national, regional, and local holidays affect sales?<br>Are holidays beneficial for all stores? |
| 🏪 Store Performance | Which stores consistently generate higher sales?<br>Are certain stores more difficult to forecast? |
| 📦 Product Analysis | Which product families exhibit strong seasonality?<br>Which products have stable versus highly volatile demand? |
| 🌍 External Factors | Does oil price influence retail sales?<br>Can transaction volume improve forecasting accuracy? |

---

# 📂 Dataset Overview

The project uses multiple datasets containing:

| Dataset | Description |
|----------|-------------|
| **train.csv** | Historical Daily Sales |
| **test.csv** | Forecasting Period |
| **stores.csv** | Store Information |
| **items.csv** | Product Metadata |
| **holidays_events.csv** | Holiday Information |
| **oil.csv** | Daily Oil Prices |
| **transactions.csv** | Daily Store Transactions |

### 📌 Forecasting Granularity

> **Daily Sales at Store–Item Level**

---

# 🔄 Project Workflow

```text
Business Understanding
        │
        ▼
Data Understanding
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Baseline Forecasting
        │
        ▼
Classical Time Series Models
        │
        ▼
Machine Learning Models
        │
        ▼
Deep Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
        │
        ▼
Deployment Recommendation
```

---

# 📊 Exploratory Data Analysis

The EDA phase covers:

- Dataset Structure
- Missing Value Analysis
- Sales Distribution
- Store-Level Analysis
- Product Family Analysis
- Promotion Analysis
- Holiday Impact
- Trend Analysis
- Seasonal Analysis
- Correlation Analysis
- Outlier Detection

---

# ⚙️ Feature Engineering

## 📅 Time-Based Features

- Year
- Month
- Week
- Day of Week
- Quarter
- Weekend Indicator

### ⏳ Lag Features

- Lag-1
- Lag-7
- Lag-14
- Lag-28

### 📈 Rolling Features

- Rolling Mean
- Rolling Median
- Rolling Standard Deviation

### 🏪 Business Features

- Promotion Status
- Holiday Flag
- Oil Price
- Transactions
- Store Attributes
- Product Family
- Perishable Indicator

---

# 🤖 Forecasting Models

## Baseline Models

- Naïve Forecast
- Moving Average
- Exponential Smoothing
- Holt-Winters

## Classical Time Series

- ARIMA
- SARIMA
- SARIMAX

## Machine Learning

- Linear Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost

## Advanced Forecasting *(Future Scope)*

- Prophet
- N-BEATS
- Temporal Fusion Transformer (TFT)
- AutoGluon
- Amazon Chronos

---

# 📏 Evaluation Metrics

| Metric | Description |
|----------|-------------|
| MAE | Mean Absolute Error |
| RMSE | Root Mean Squared Error |
| MAPE | Mean Absolute Percentage Error |
| WMAPE | Weighted Mean Absolute Percentage Error |
| Training Time | Model Efficiency |
| Interpretability | Ease of Business Adoption |

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn, XGBoost, LightGBM, CatBoost |
| Time Series | Statsmodels, Prophet |
| Development | Google Colab |
| Version Control | Git & GitHub |

---

# 📁 Repository Structure

```text
Retail-Demand-Forecasting/
│
├── docs/
├── notebooks/
├── data/
├── outputs/
├── src/
└── README.md
```

---

# 🚀 Current Progress

| Phase | Status |
|--------|--------|
| ✅ Business Understanding | Completed |
| 🚧 Data Understanding | In Progress |
| ⏳ Exploratory Data Analysis | Pending |
| ⏳ Feature Engineering | Pending |
| ⏳ Baseline Models | Pending |
| ⏳ Machine Learning Models | Pending |
| ⏳ Advanced Forecasting Models | Pending |
| ⏳ Final Report | Pending |

---

# 📌 Future Scope

- Prophet
- N-BEATS
- Temporal Fusion Transformer (TFT)
- AutoGluon
- Amazon Chronos
- Hyperparameter Optimization
- Streamlit Dashboard
- Model Deployment

---

# ⭐ Expected Deliverables

- Complete EDA Report
- Feature Engineering Pipeline
- Multiple Forecasting Models
- Model Performance Comparison
- Business Insights
- Production Recommendations
- GitHub-ready Documentation

---

## 👩‍💻 Author

**Dipti Gupta**

*M.Tech | Business Data Analyst | Aspiring Data Scientist*
