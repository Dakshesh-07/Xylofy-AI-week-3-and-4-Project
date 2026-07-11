# Xylofy-AI-week-3-and-4-Project
# 📦 End-to-End Sales Forecasting & Demand Intelligence System

**Author:** Dakshesh Verma  
**Date:** July 2026  

## 🎯 Project Overview
Every retail and e-commerce company relies on accurate demand prediction. Overstocking wastes capital and storage, while understocking leads to lost revenue and customer dissatisfaction. 

This project is an end-to-end data science solution designed to solve this exact problem. Using 4 years of historical daily sales data, this system predicts future product demand, detects unusual sales anomalies (spikes/drops), segments products based on their demand behavior, and serves these insights through an interactive web dashboard.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Forecasting Models:** SARIMA (`statsmodels`), Facebook Prophet, XGBoost
* **Machine Learning:** `scikit-learn` (Isolation Forest, K-Means Clustering)
* **Visualization:** Matplotlib, Seaborn
* **Deployment:** Streamlit

## 📁 Repository Structure
```text
SalesForecasting_DaksheshVerma/
│
├── analysis.ipynb       # Complete Jupyter/Colab notebook with EDA, modeling, and clustering
├── app.py               # Streamlit dashboard application code
├── requirements.txt     # Python dependencies for deployment
├── summary.pdf          # 2-page Executive Business Report (Insights & Strategy)
├── train.csv            # The Superstore sales dataset used for training
└── charts/              # Directory containing exported visual assets for the dashboard
    ├── anomaly_chart.png
    └── forecast_chart.png
