# Telecom Customer Churn Prediction

Machine learning project for predicting customer churn in the telecom industry.

## Project Overview

Customer churn prediction is one of the key business tasks for telecom companies. Retaining existing customers is typically more cost-effective than acquiring new ones. This project focuses on building a machine learning model to identify customers who are likely to leave the service.

## Objective

Develop and compare machine learning models for customer churn prediction using customer demographics, contract information, subscribed services, and account data.

## Dataset

The project uses an educational telecom customer dataset containing information about:

- customer demographics;
- contract details;
- internet and phone services;
- billing information;
- customer churn status.

**Note:** The original dataset is not included in this repository in accordance with the educational platform policy.

## Project Workflow

- Data loading and validation
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and comparison
- Hyperparameter tuning
- Model evaluation
- Feature importance analysis
- Business recommendations

## Models

The following models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- CatBoost
- Multi-Layer Perceptron (MLP)

Model selection was performed using cross-validation with ROC-AUC as the primary evaluation metric.

## Results

| Metric | Value |
|---------|------:|
| Best Model | CatBoost |
| ROC-AUC | **0.913** |
| Accuracy | **0.919** |

The CatBoost model achieved the best predictive performance on the test dataset.

## Key Findings

The analysis identified the following factors as the most important for predicting customer churn:

- contract type;
- customer tenure;
- monthly charges;
- internet service type;
- payment method;
- additional service subscriptions.

Customers with shorter contracts and higher monthly charges showed a higher probability of churn.

## Business Recommendations

The developed model can be used to identify customers at risk of churn and support customer retention strategies.

Recommended actions include:

- targeted retention campaigns;
- personalized offers;
- proactive customer support;
- additional incentives for high-value customers;
- increased attention to new customers.

## Tech Stack

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- CatBoost
- PyTorch
- SQLAlchemy
