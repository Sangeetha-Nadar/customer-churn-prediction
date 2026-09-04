# Customer Churn Prediction

A machine learning-based web application that predicts whether a customer is likely to churn and provides a churn probability, risk level, and personalized retention recommendations.

## Project Overview

Customer churn prediction helps businesses identify customers who are at risk of leaving and take proactive retention actions. This project uses a trained XGBoost classification model to analyze customer information and estimate the probability of churn.

The application provides an interactive web interface where users can enter customer details and receive real-time churn predictions along with risk classification and recommended retention strategies.

## Key Features

- Customer churn prediction using XGBoost
- Churn probability calculation
- Risk classification:
  - 🟢 LOW
  - 🟡 MEDIUM
  - 🟠 HIGH
  - 🔴 CRITICAL
- Personalized customer retention recommendations
- Interactive prediction interface
- REST API endpoint for predictions
- Batch prediction using CSV files
- Backend data validation using Pandas
- Prediction logging
- Model and preprocessor validation
- Health-check endpoint for application monitoring

## Technologies Used

- Python
- FastAPI
- XGBoost
- Scikit-learn
- Pandas
- HTML
- CSS
- JavaScript
- Jinja2
- REST API
- Uvicorn

## Input Features

The model uses customer attributes such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Credit Card Status
- Active Member Status
- Estimated Salary

## Output

The application provides:

- Churn prediction
- Churn probability
- Customer risk level
- Risk indicator
- Personalized retention suggestions

## Purpose

The goal of this project is to demonstrate the practical implementation of a machine learning model in a web application and provide businesses with actionable insights for customer retention.
