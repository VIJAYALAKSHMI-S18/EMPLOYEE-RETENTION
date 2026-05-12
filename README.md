# EMPLOYEE-RETENTION
---

👩‍💼 Employee Retention Prediction System

📌 Overview

This project is a Machine Learning-based classification system that predicts whether an employee will leave the company or stay based on HR data.
The model is built using Logistic Regression.


---

🎯 Problem Statement

To build a model that predicts employee turnover (left = 0 or 1) using HR and workplace-related features.


---

📊 Dataset

File: HR_comma_sep.csv

Target Variable: left

0 → Stayed

1 → Left




---

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn



---

🤖 Machine Learning Model

Algorithm: Logistic Regression

Type: Binary Classification

Output: Probability of employee leaving



---

🔄 Project Workflow

1. Data Loading and Exploration


2. Data Preprocessing


3. Feature Engineering (One-hot encoding for salary)


4. Train-Test Split


5. Model Training using Logistic Regression


6. Model Evaluation


7. Visualization




---

📈 Model Evaluation

Accuracy score on test data

Prediction probabilities

Model coefficients and intercept



---

📊 Visualization

Relationship between Satisfaction Level vs Employee Leaving



---

💾 Model File

If saved, model is stored as:

model.pkl


---

📦 Installation

Install dependencies:

pip install -r requirements.txt


---

▶️ How to Run

python app.py


---

🧠 Key Insight

Employees with low satisfaction levels are more likely to leave the company.
