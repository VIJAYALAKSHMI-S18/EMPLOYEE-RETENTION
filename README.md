# EMPLOYEE-RETENTION
👩‍💼 Employee Retention Prediction
Overview
This project uses Machine Learning (Logistic Regression) to predict whether an employee will leave the company or stay based on HR data.
Problem Statement
Predict employee turnover (left = 0 or 1) using workplace and demographic features.
Dataset
File: HR_comma_sep.csv
Target: left
0 → Stayed
1 → Left
Features Used
satisfaction_level
last_evaluation
number_project
average_montly_hours
time_spend_company
Work_accident
promotion_last_5years
salary
Tech Stack
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Model
Logistic Regression (Binary Classification)
Workflow
Load dataset
Preprocess data (one-hot encoding for salary)
Split data into train/test sets
Train Logistic Regression model
Make predictions
Evaluate accuracy
Visualize results
Evaluation
Accuracy score using test data
Prediction probabilities
Model coefficients
Visualization
Satisfaction level vs Employee leaving (scatter plot)
How to Run
Bash
pip install pandas numpy matplotlib scikit-learn
Bash
python app.py
Key Insight
Lower satisfaction levels strongly indicate higher chances of employee attrition.
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