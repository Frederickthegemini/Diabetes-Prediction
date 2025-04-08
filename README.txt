Diabetes Risk Prediction

This project builds a predictive model to assess the likelihood of diabetes in patients based on health-related variables. It walks through data cleaning, exploration, machine learning, and evaluation, providing actionable insights for healthcare professionals.

📊 Dataset

Source: diabetes.csv (Pima Indians Diabetes Database)

Features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (Target: 1 = diabetic, 0 = non-diabetic)

🎯 Business Problem

Healthcare systems aim to identify individuals at high risk of diabetes early on. This model helps predict a patient's diabetes status using basic diagnostic measurements, allowing for targeted prevention or further testing.

🛠️ Tools & Libraries

Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn

📈 Project Workflow

Data Cleaning

Replaced 0s in medical features with NaNs

Imputed missing values with medians

Exploratory Data Analysis (EDA)

Visualized outcome distribution

Analyzed feature correlations

Feature Scaling

Used StandardScaler to normalize variables

Modeling

Logistic Regression for interpretability

Random Forest for performance comparison

Evaluation

Confusion Matrix

Precision, Recall, F1 Score

ROC Curve & AUC

🔍 Results

Key predictors: Glucose, BMI, Age

Logistic Regression AUC: ~0.83

Random Forest slightly outperformed in accuracy & recall

📌 How to Run

Clone this repo

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Run diabetes_notebook.ipynb

📬 Contact

For questions or suggestions, feel free to reach out or open an issue.

