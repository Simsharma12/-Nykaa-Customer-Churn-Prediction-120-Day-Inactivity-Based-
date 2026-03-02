# -Nykaa-Customer-Churn-Prediction-120-Day-Inactivity-Base
## 📌 Project Overview

This project focuses on predicting customer churn for Nykaa (an online beauty & lifestyle platform).

Churn is defined as customers who have not made a purchase for more than 120 days.

The objective is to understand:
- Why customers become inactive after sale periods
- Whether discount dependency increases churn risk
- How Nykaa Prive membership impacts customer retention
- 
## 🎯 Business Problem

Nykaa observes that many customers purchase heavily during sale events 
(60–75% discount periods) but become inactive afterward.
The goal is to:
- Identify customers at risk of churn
- Analyze behavioral patterns leading to inactivity
- Provide actionable business insights for retention strategies

## 📂 Dataset Features

Key features used:

- pre_sale_purchases
- sale_purchases
- post_sale_purchases
- discount_usage_percent
- prive_tier (None / Prive / Gold / Platinum)
- prive_points
- returns_count
- customer_support_tickets
- avg_order_value
- days_since_last_purchase
- churn (Target Variable)
- 
## 🤖 Algorithms Used

- Logistic Regression (Baseline Model)
- Random Forest Classifier (Final Model)
These models were selected to compare linear and non-linear approaches 
for predicting customer churn based on behavioral and membership features.

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall (Important for churn detection)
- F1 Score
- ROC-AUC Score

