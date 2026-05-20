# 🤖 AI-Powered Customer Churn Intelligence System

> **Predict. Explain. Visualize. Recommend. Report.**

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python) ![XGBoost](https://img.shields.io/badge/XGBoost-ML-orange) ![SHAP](https://img.shields.io/badge/SHAP-Explainability-green) ![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow) ![GitHub](https://img.shields.io/badge/Portfolio-Ready-purple)

---

## 📋 Project Overview

This project is a **complete, end-to-end AI analytics system** designed to predict customer churn, explain the behavioral risk factors behind every prediction, and translate those findings into actionable business retention strategies — all presented through an executive-grade Power BI dashboard.

This is not a simple model-training exercise. It is a **production-grade analytics pipeline** covering:

- ✅ Data cleaning and preparation
- ✅ Feature engineering with business logic
- ✅ Machine learning with Logistic Regression, Random Forest, and XGBoost
- ✅ Churn risk scoring (probability-based segmentation)
- ✅ SHAP explainability for every prediction
- ✅ Power BI executive dashboard (4 pages)
- ✅ Business KPIs including Revenue at Risk
- ✅ Retention strategy recommendations

---

## 🏢 Business Problem

Customer churn is one of the most expensive problems in subscription-based businesses. Acquiring a new customer costs **5–7× more** than retaining an existing one. Without early warning systems, companies react to churn instead of preventing it.

**This system answers three critical business questions:**
1. *Which customers are most likely to churn in the next period?*
2. *Why are they at risk — and what specific behaviors drive that risk?*
3. *What targeted actions should the business take to retain them?*

---

## 📊 Dataset

**IBM Telco Customer Churn Dataset**
- Source: [Kaggle — IBM Telco Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- ~7,043 customer records
- 21 features including tenure, monthly charges, contract type, internet service, payment method
- Binary target: `Churn = Yes / No`

---

## 🔧 Tech Stack

| Purpose | Tool |
|---|---|
| Coding & ML | Google Colab / Jupyter |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Advanced Model | XGBoost |
| Explainability | SHAP |
| Data Visualization | Matplotlib, Seaborn |
| BI Dashboard | Power BI |
| Version Control | GitHub |

---

## 🏗️ Project Architecture

```
RAW DATA
   ↓
DATA CLEANING
   ↓
FEATURE ENGINEERING
   ↓
ML MODEL TRAINING
   ↓
CHURN PREDICTION
   ↓
SHAP EXPLAINABILITY
   ↓
EXPORT RESULTS
   ↓
POWER BI DASHBOARD
   ↓
BUSINESS RECOMMENDATIONS
```

---

## 📁 Repository Structure

```
ai-customer-churn-intelligence/
│
├── data/
│   ├── raw/                  # Original dataset (WA_Fn-UseC_-Telco-Customer-Churn.csv)
│   └── processed/            # Cleaned + feature-engineered export
│       └── churn_dashboard_data.csv
│
├── notebooks/
│   └── churn_intelligence_system.ipynb   # Full end-to-end ML notebook
│
├── dashboard/
│   ├── churn_dashboard.pbix              # Power BI dashboard file
│   └── screenshots/                      # Dashboard page screenshots
│       ├── page1_executive_overview.png
│       ├── page2_risk_segmentation.png
│       ├── page3_churn_drivers.png
│       └── page4_retention_recommendations.png
│
├── reports/
│   └── executive_summary.md              # Non-technical business summary
│
├── architecture/
│   └── system_architecture.png           # Architecture diagram
│
└── README.md
```

---

## 🤖 Machine Learning Models

| Model | Purpose | ROC-AUC |
|---|---|---|
| Logistic Regression | Baseline interpretable model | ~0.83 |
| Random Forest | Ensemble — handles non-linearity | ~0.88 |
| **XGBoost** | **Primary model — best performance** | **~0.92** |

All models evaluated on 80/20 train-test split with stratified sampling.

---

## 📈 Key Business KPIs

- **Total Customers Analyzed**
- **Overall Churn Rate (%)**
- **Revenue at Risk (USD)** — `MonthlyCharges × ChurnProbability`
- **High-Risk Customer Count**
- **Medium-Risk Customer Count**
- **Predicted Retention Savings**

---

## 🔍 SHAP Explainability

SHAP (SHapley Additive exPlanations) breaks open the XGBoost "black box" and explains **why** each customer received their risk score.

Top churn drivers identified:
1. **Month-to-month contract** → highest churn signal
2. **High monthly charges (>$80)** → strong positive churn predictor
3. **Short tenure (<12 months)** → early churn window
4. **Fiber optic internet service** → elevated churn risk
5. **Electronic check payment** → correlated with churn behavior

---

## 💼 Power BI Dashboard (4 Pages)

| Page | Content |
|---|---|
| 1 — Executive Overview | Total customers, churn rate, revenue at risk, KPI cards |
| 2 — Risk Segmentation | High/Medium/Low risk distribution, churn by tenure & contract |
| 3 — Churn Drivers | SHAP feature importance, behavioral analysis |
| 4 — Retention Recommendations | Rule-based action table, intervention matrix |

---

## 💡 Retention Recommendations

| Risk Pattern | Recommended Action |
|---|---|
| High monthly charges (>$80) | Offer loyalty discount or bundle |
| Month-to-month contract | Incentivize annual contract upgrade |
| Tenure < 6 months | Enhanced onboarding + check-in program |
| No tech support + fiber | Proactive support outreach |
| Electronic check payment | Migrate to auto-pay for better retention |

---

## 🚀 How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/lrcataytay00745-spec/ai-customer-churn-intelligence.git
   ```
2. **Open the notebook in Google Colab:**
   - Upload `notebooks/churn_intelligence_system.ipynb` to [colab.research.google.com](https://colab.research.google.com)
3. **Upload the dataset:**
   - Download from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
   - Upload as `/content/customer_churn.csv` in Colab
4. **Run all cells** — the notebook is fully sequential and self-documented
5. **Download** `churn_dashboard_data.csv` from Colab
6. **Open Power BI Desktop** → Load the CSV → Open `dashboard/churn_dashboard.pbix`

---

## 🎯 Portfolio Value

This project positions you as:
- Junior Data Analyst
- BI Analyst
- Customer Analytics Specialist
- Entry-Level Data Scientist
- Product Analytics Candidate

---

## 📄 Resume Description

> *Developed an AI-powered customer churn intelligence system using Python, XGBoost, SHAP, and Power BI to predict customer churn, identify behavioral risk factors, and support retention strategy recommendations through interactive executive dashboards.*

---

*Built as a portfolio project by a graduate student in Economics & Data Analytics — Davao, Philippines 🇵🇭*
