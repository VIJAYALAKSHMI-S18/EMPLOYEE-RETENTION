# EMPLOYEE-RETENTION
👩‍💼 Employee Retention Prediction System
📌 Overview
This project is a Machine Learning-based classification system that predicts whether an employee will leave the company or stay based on HR data.
It uses Logistic Regression and is built using Python and Scikit-learn.
The goal is to help companies understand employee behavior and improve retention strategies.
🎯 Problem Statement
To build a model that predicts whether an employee will leave the company (left = 1) or stay (left = 0) based on HR features like satisfaction level, salary, working hours, and more.
📊 Dataset
File: HR_comma_sep.csv
🔑 Features Used:
satisfaction_level
last_evaluation
number_project
average_montly_hours
time_spend_company
Work_accident
promotion_last_5years
salary (categorical)
🎯 Target Variable:
left
0 → Stayed
1 → Left
⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib 📊
Scikit-learn
🤖 Machine Learning Model
Algorithm: Logistic Regression
Type: Binary Classification
Output: Probability of employee leaving the company
🔄 Project Workflow
Import libraries and dataset
Data exploration (shape, head)
Feature selection and target separation
One-hot encoding for categorical data (salary)
Train-test split
Model training using Logistic Regression
Prediction on test data
Model evaluation (accuracy score)
Visualization (satisfaction vs employee leaving)
📈 Model Evaluation
Accuracy is calculated using:
Python
model.score(X_test, y_test)
Additional outputs:
Predictions (y_predicted)
Probabilities (predict_proba)
Model coefficients (coef_)
Intercept (intercept_)
📊 Visualization
A scatter plot is used to understand relationship between:
Satisfaction Level vs Employee Leaving
▶️ How to Run
Bash
pip install pandas numpy matplotlib scikit-learn
Run the script:
Bash
python your_file_name.py
📌 Key Insight
Employees with low satisfaction levels are more likely to leave the company.
🚀 Future Improvements
Add Streamlit web app for live prediction
Try advanced models (Random Forest, XGBoost)
Feature engineering for better accuracy
Deploy as a web application