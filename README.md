# Fraud Detection using Bank Marketing Campaign Dataset

## Dataset Summary
- Total Records: **45,211**
- Columns: **17**
- All data is clean and contains **no missing values**

## Fraud Simulation
A new `fraud` column was engineered based on financial and categorical patterns to mimic realistic fraudulent behavior.

- **Fraud Cases:** 1,635
- **Non-Fraud Cases:** 43,576

## Insights
- Fraud is most common in jobs like **management**, **technician**, **blue-collar**, **admin**, and **services**
- Fraud cases tend to have **balances below 1,500**
- **Housing loan = yes** is frequent in fraud cases
- Fraud cases usually **do not have personal or default loans**

## ML Performance
- **Model Used:** Random Forest Classifier
- **Accuracy:** 100%
- **Precision, Recall, F1-score:** 1.00 for both classes
- **Confusion Matrix Output:**
  - 13,073 Non-Fraud cases predicted correctly
  - 491 Fraud cases predicted correctly
- **Isolation Forest** further validated outlier-based fraud patterns

## Requirements

Install all required packages using the following command:

```bash
pip install -r requirements.txt
