# 🛒 E-Commerce Customer Churn Analysis

## 🎯 Business Problem
97% of Olist e-commerce customers never returned after their first purchase.
This project identifies WHY customers churn and predicts WHO will churn next.

## 📦 Dataset
- Source: Olist Brazilian E-Commerce (Kaggle)
- Size: 93,358 customers | 100,000+ orders | 2016–2018
- Tables: Orders, Customers, Payments, Items, Reviews

## 🔧 Tools Used
Python · Pandas · Scikit-learn · Matplotlib · Seaborn

## 🔍 Key Findings
1. **97% churn rate** — nearly all customers are one-time buyers
2. **tenure_days** is the #1 churn predictor (0.61 feature importance)
3. **Champions segment** (8,600 customers) has the lowest churn at 83%
4. **Lost + Hibernating** segments show 100% churn probability

## 🤖 Model Performance
| Model | AUC Score |
|-------|-----------|
| Random Forest | 0.9854 |
| Logistic Regression | 0.9888 |

## 💡 Business Recommendations
1. **Retention campaign**: Target new customers within 30 days of first purchase
2. **Reward Champions**: Loyalty program for the 8,000 champion customers
3. **Win-back campaign**: Special offers for 14,648 hibernating customers

## 📁 Project Structure
```
ecommerce-churn/
├── data/               ← raw CSV files
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_cleaning.ipynb
│   └── 04_model.ipynb
└── outputs/            ← saved charts
```

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```# ecommerce-churn-analysis
