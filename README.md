# Neo_bank_project

CODE LINK : https://colab.research.google.com/drive/1lD-_hUWk6CjdIMl_W3SV8zGnK84qPJk7?usp=sharing

🧠 Customer Churn Prediction Project
🔗 Open in Google Colab

This project was developed as part of the Le Wagon Data Analytics Bootcamp and focuses on predicting customer churn by analyzing user behavior across multiple data sources.

📌 Objective
The main goal is to identify churned vs. non-churned customers using features derived from the following datasets:

devices

users

transactions

By combining these tables and engineering relevant features, the model aims to understand patterns that signal potential customer churn.

🧪 Statistical Feature Selection
To identify the most informative features, several statistical tests were applied:

Mann-Whitney U Test – for comparing numerical feature distributions between churn and non-churn groups

Kolmogorov-Smirnov (KS) Test – for assessing distribution differences

Chi-Square Test – for evaluating the relationship between categorical features and churn status

🤖 Machine Learning Models
Two supervised learning algorithms were used to build and evaluate churn prediction models:

Logistic Regression – as a baseline model for binary classification

Random Forest – for capturing nonlinear relationships and feature interactions

To address class imbalance (common in churn datasets), the SMOTE (Synthetic Minority Over-sampling Technique) method was applied, improving model performance by generating synthetic samples of the minority class (churned users).

🧰 Tools & Libraries Used
pandas – data manipulation and analysis

matplotlib.pyplot – data visualization

scikit-learn – model training, evaluation, and preprocessing

PyCaret – streamlined model comparison and tuning

imblearn – SMOTE oversampling for class balancing

