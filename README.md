
# E-Commerce Customer Satisfaction Prediction using Deep Learning

## Project Overview

This project focuses on predicting Customer Satisfaction (CSAT) scores for ecommerce customer support interactions. Customer satisfaction is a key metric for measuring service quality, customer retention, and operational efficiency.

The objective of this project is to build a machine learning model that predicts CSAT scores based on customer support interaction data such as communication channel, handling time, issue type, and customer attributes.

By predicting CSAT in advance, businesses can proactively improve customer experience and reduce dissatisfaction.

---

# Objectives

### CSAT Prediction
Develop a Deep Learning model to predict customer satisfaction scores.

### Customer Experience Analysis
Identify key factors affecting customer satisfaction.

### Operational Efficiency
Improve customer support processes using predictive insights.

### Proactive Intervention
Enable early identification of dissatisfied customers.

---

# Steps to Solve the Problem

## Problem Identification

Ecommerce companies handle a large number of customer support queries. Monitoring customer satisfaction manually is difficult and inefficient.

This project builds a predictive model that automatically forecasts CSAT scores, allowing businesses to take proactive actions.

---

# Data Collection

The dataset contains ecommerce customer support interaction data.

## Dataset Features

Key attributes include:

- Communication Channel
- Issue Category
- Sub-category
- Agent Shift
- Handling Time
- Customer Tenure
- Product Category
- Order Details
- CSAT Score (Target Variable)

These features influence customer satisfaction levels.

---

# Data Preprocessing

Several preprocessing steps were performed:

### Handling Missing Values
Missing values were identified and treated appropriately.

### Removing Duplicates
Duplicate records were removed.

### Encoding Categorical Variables
Categorical features were converted into numerical format.

### Feature Scaling
Numerical variables were scaled for better model performance.

---

# Exploratory Data Analysis (EDA)

EDA helped identify patterns in customer satisfaction.

## Key Insights

- Handling time significantly impacts CSAT scores.
- Communication channel affects customer satisfaction.
- Certain issue categories lead to lower CSAT.
- Customer tenure influences satisfaction levels.
- Agent shift variations affect performance.

Visualizations were created using Matplotlib and Seaborn.

---

# Machine Learning Models Used

Multiple classification models were tested:

### Logistic Regression
Baseline model for CSAT prediction.

### Decision Tree Classifier
Captured non-linear relationships.

### Random Forest Classifier
Improved accuracy using ensemble learning.

### Gradient Boosting Models
Enhanced performance using boosting techniques.

---

# Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

The best-performing model was selected based on balanced performance.

---

# Key Features of the Solution

- Predicts customer satisfaction scores
- Identifies factors affecting customer experience
- Helps reduce customer churn
- Improves support team performance
- Enables proactive customer engagement

---

# Technologies Used

## Programming Language
Python

## Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

# Results

The machine learning model successfully predicts CSAT scores using customer support data. The solution helps ecommerce businesses identify dissatisfied customers and improve service quality.

---

# Conclusion

This project demonstrates how machine learning can be used to predict customer satisfaction in ecommerce customer support.

By combining data preprocessing, exploratory data analysis, and classification models, the system provides actionable insights to improve customer experience.

Such predictive systems help businesses enhance service quality, increase retention, and optimize operations.
