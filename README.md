Overview

This project presents an in-depth exploratory data analysis (EDA) of real-world credit card transactions to uncover patterns and indicators of fraudulent activity. Using Pandas, NumPy, Matplotlib, and Seaborn, the analysis visualizes class imbalance, explores feature distributions, investigates time-based fraud patterns, and quantifies the financial impact of fraud.

Dataset:
Credit Card Fraud Detection Dataset (Kaggle)

    284,807 transactions

    492 frauds (highly imbalanced)

    Features: anonymized (V1–V28), Amount, Time, Class (1 = fraud, 0 = legit)
Project Highlights

    Class Imbalance Analysis: Quantifies and visualizes the rarity of fraud.

    Feature Distribution Comparison: Identifies features most correlated with fraud.

    Outlier & Loss Analysis: Examines monetary loss and feature outliers.

    Time-Based Patterns: Reveals hourly fraud risk and transaction timing.

    Actionable Insights: Summarizes findings for business and analytics teams.
Results & Insights

    Fraudulent transactions are less than 0.2% of all transactions but cause significant monetary loss.

    Key features (V14, V10, V12) show strong separation between fraud and non-fraud.

    Fraud rates spike at specific hours, suggesting targeted monitoring could be effective.

    Outlier transactions (by amount or feature values) are more likely to be fraudulent.
