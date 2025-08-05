# 📊 Sales Forecasting & Feature Impact Dashboard

This Power BI project demonstrates a comprehensive sales forecasting and explainability analysis using **LSTM**, **SHAP**, and **Power BI**.

It showcases how to integrate predictive modeling with interpretable visuals to support data-driven decisions in retail or supply chain environments.

---

## 🚀 Project Overview

**Objective:**  
To accurately forecast short-term daily sales using deep learning (LSTM) and visualize the key demand drivers through SHAP values.

**Key Goals:**
- Improve forecast accuracy using external signals and multivariate time series
- Provide explainability to non-technical stakeholders
- Enable scenario-based decision making through interactive dashboards

---

## 🧠 Key Features

- 📈 **Actual vs Forecast Sales** (with confidence intervals)
- 🎯 **KPI Cards** for MAPE, MAE, RMSE
- 🔍 **SHAP Feature Importance** by attribute
- 🧮 **MAPE by Attribute** breakdown
- 🧰 **Custom Tooltips** with clean pop-up summaries
- 📆 **Calendar-Based Filtering** (Year, Quarter, Month, Day)

---

## 🛠️ Tools & Technologies

| Category     | Tools Used                                    |
|--------------|-----------------------------------------------|
| Data Modeling| Python (LSTM, Prophet, SHAP), Pandas, NumPy   |
| Forecasting  | LSTM Neural Network & Prophet Baseline        |
| Explainability| SHAP (TreeExplainer / DeepExplainer)         |
| BI & Visualization | Power BI (KPI Cards, Tooltips, DAX)    |
| Scripting    | Jupyter / Google Colab for model training     |

---

## 📂 File Structure

```plaintext
/Sales-Forecasting-PowerBI/
├── PowerBI_Sales_Forecast.pbix         # Final Power BI report
├── data/
│   ├── final_timeseries.csv            # Actual daily sales
│   ├── prophet_forecast.csv            # Model forecast outputs
│   ├── shap_feature_importance.csv     # SHAP values
├── images/
│   └── dashboard_preview.png           # Preview for README/LinkedIn
├── README.md
