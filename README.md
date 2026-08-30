# Customer Churn Prediction

Predicting telecom customer churn by training and comparing five machine
learning models, based on 7,043 historical customer records across 20
features (demographics, subscribed services, account details).

## Problem
Telecom companies lose significant revenue when customers churn (cancel
service). Acquiring new customers costs far more than retaining existing
ones, making early churn prediction valuable for targeted retention offers.

## Models Compared

| Model                          | Accuracy | Recall (Churners) |
|---------------------------------|----------|--------------------|
| Logistic Regression (Benchmark) | 81%      | 56% — Best overall performer |
| XGBoost                         | 79%      | 54%                |
| Artificial Neural Network       | 80%      | 49%                |
| Decision Tree                   | 73%      | 49%                |
| Random Forest                   | 79%      | 41%                |

**Result:** Logistic Regression, despite being the simplest baseline,
outperformed more complex models on both accuracy and recall for
identifying at-risk customers.

## Dataset
Telco Customer Churn dataset (IBM/Kaggle, public).

## Stack
Python, scikit-learn, XGBoost, TensorFlow/Keras, pandas, seaborn, plotly
