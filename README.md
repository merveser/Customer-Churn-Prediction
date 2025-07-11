# Telco Customer Churn Prediction

A comprehensive machine learning project to predict customer churn in the telecommunications industry using classification algorithms.

## Project Overview

This project analyzes customer data to identify patterns and predict which customers are likely to churn (cancel their service). The goal is to help telecom companies proactively retain valuable customers through data-driven insights.

## Dataset
- **Source**: Kaggle Telco Customer Churn Dataset
- **Features**: Customer demographics, services, account information, and churn status
- **Target**: Binary classification (Churn: Yes/No)

## Project Workflow

1. **Exploratory Data Analysis (EDA)** - Dataset overview and initial insights
2. **Data Cleaning & Type Conversion** - Data quality assessment and preparation
3. **Feature Classification** - Numerical vs categorical feature identification
4. **Outlier Analysis** - Detection and handling of anomalous data points
5. **Data Preprocessing** - Encoding, scaling, and transformation
6. **Train-Validation-Test Split** - Data partitioning for model evaluation
7. **Model Development** - Implementation of multiple classification algorithms
8. **Model Comparison** - Performance evaluation and selection

## Models Implemented

- **Logistic Regression** ⭐ (Best Performer)
- **K-Nearest Neighbors (KNN)**
- **Random Forest** (with hyperparameter tuning)

## Key Results

| Model | Accuracy | F1-Score | AUC |
|-------|----------|----------|-----|
| Logistic Regression | 0.7946 | 0.5628 | 0.8315 |
| Random Forest (Tuned) | - | 0.5263 | 0.8343 |
| KNN | 0.7790 | 0.4534 | 0.7694 |

## Conclusion

**Logistic Regression** emerged as the optimal model for this churn prediction task, offering:
- **Best F1-Score** (0.5628) for identifying churned customers
- **High AUC** (0.8315) indicating excellent discrimination ability
- **Superior interpretability** for business stakeholders
- **Balanced performance** across all evaluation metrics

The model successfully identifies customers at risk of churning, enabling targeted retention strategies and improved customer lifetime value.

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

