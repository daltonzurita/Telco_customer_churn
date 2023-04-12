# Telco Customer Churn

This project focuses on predicting customer churn for a telecommunications company using various machine learning models. Customer churn is the loss of clients or customers, and understanding the factors that contribute to churn can help businesses improve their customer retention strategies.

## Dataset

The dataset used in this project is the [IBM Watson Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn). It contains information about customer demographics, services they've subscribed to, and whether they've churned or not.

## Features

Some of the features in the dataset include:

- Customer demographics: gender, age, and whether they have dependents
- Account information: how long they've been a customer, contract, payment method, paperless billing, and monthly charges
- Services: phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

## Models

In this project, various machine learning models are used and compared to predict customer churn, including:

- XGBoost
- Random Forest Classifier
- Support Vector Machine

## Usage

1. Download the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn) and place it in the same directory as the Jupyter notebook.
2. Open the Jupyter notebook "Telco_customer_churn.ipynb" and run all the cells.

## Results

The performance of the models is evaluated using F1 score, which considers both precision and recall. The model with the highest F1 score is considered the best performing model for predicting customer churn in this dataset.
