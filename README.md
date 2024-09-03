# BUSA8001 - APPLIED PREDICTIVE ANALYTICS

**Full name**: Dang Ha Nguyen (Janice) Nguyen

**ID**: 47856491

**Repository**: [GitHub Repository](https://github.com/JaniceNguyen/BUSA8001_Assignment1)

## Introduction

### Project Overview

This project involves analyzing a dataset provided by a financial institution to understand the credit behavior of its clients. The analysis is based on two primary datasets: `application_record.csv` and `credit_record.csv`. The objective is to preprocess the data, explore it, and develop predictive models that can help identify clients who are at risk of defaulting on their loans.

### Problem Statement

The specific problem this project aims to solve is the identification of clients who are likely to default on their loans. The goal is to use historical application and credit data to build a model that can accurately predict whether a client will default based on their past credit records and application data.

### Data Description

Two main datasets are used:

1. `application_record.csv`: Contains detailed information about the clients.
2. `credit_record.csv`: Provides a monthly record of the clients' credit status.

## Methodology

The project follows these main steps:

1. **Data Loading and Merging**: Importing and combining the datasets.
2. **Data Cleaning and Preprocessing**: Handling missing values, encoding categorical variables.
3. **Feature Engineering**: Creating new features and transforming existing ones.
4. **Model Training**: Implementing Logistic Regression and Random Forest classifiers.
5. **Model Evaluation**: Comparing model performances using accuracy metrics.

## Key Findings

1. **Data Insights**: The merged dataset revealed multiple credit records per client over different months.
2. **Missing Data**: Some variables like education type and occupation had missing values, which were imputed.
3. **Model Performance**:
   - Logistic Regression: Training Accuracy: 0.655, Test Accuracy: 0.656
   - Random Forest: Training Accuracy: 0.975, Test Accuracy: 0.903
4. **Nonlinearities**: The significant performance difference between models suggests the presence of nonlinear relationships in the data.

## Conclusion

The Random Forest model outperformed Logistic Regression, indicating its better capability to capture complex patterns in credit default prediction. The high accuracy (90.3% on test data) suggests it could be a valuable tool for the financial institution in assessing credit risk.

## Future Work

- Feature Engineering: Create new features capturing important aspects of credit risk.
- Time Series Analysis: Incorporate more sophisticated analysis of temporal credit behavior.
- Model Interpretability: Implement techniques like SHAP values for better model interpretation.

## Potential Applications

This analysis could be extended to similar datasets in the financial sector, such as:
- Predicting early loan repayments
- Estimating the probability of customers opening new accounts or services
- Detecting fraudulent transactions

By continually refining these models and expanding their applications, financial institutions can make more informed decisions, manage risk more effectively, and provide better services to their clients.