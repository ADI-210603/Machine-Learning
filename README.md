📘 Project Overview

This project builds a Loan Approval Prediction System using Machine Learning.
It predicts whether a customer’s loan application should be Approved or Not Approved, based on their financial profile, loan history, and demographic details.

The project includes:

✔ Data Cleaning
✔ Exploratory Data Analysis (EDA)
✔ Feature Engineering
✔ Data Encoding
✔ Scaling
✔ SMOTE for class balancing
✔ Model Training (Logistic Regression, Random Forest, XGBoost)
✔ Model Evaluation
✔ Final Prediction Function
✔ Ready-to-use ML Pipeline

🎯 Objective

Financial institutions receive thousands of loan applications every month.
Manual verification is slow and error-prone.

The objective of this project is to:

Predict Loan Approval Status

Identify high-risk applicants

Improve decision-making for banks

Reduce default risk

📂 Dataset Details

Total Records: ~52,000

Features: 26 independent features

Target Variable: Loan_Approval_Status

Data Type: Structured, Tabular

Source: Kaggle

Key Columns Used:

Applicant demographics

Income & expenses

Credit score

Existing loans

Loan purpose

Interest rate

Transaction behavior

Default risk

Co-applicant information

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

XGBoost

Imbalanced-Learn (SMOTE)

Jupyter Notebook

📊 Project Workflow
1️⃣ Data Cleaning

Removed missing values

Corrected data types

Removed duplicates

Identified outliers

2️⃣ Exploratory Data Analysis (EDA)

Visualized:

Income distribution

Credit score patterns

Loan amount vs approval

Loan purpose breakdown

Default risk patterns

Correlation heatmap

3️⃣ Feature Engineering

Label Encoding for categorical columns

Scaling numerical columns

Handling skewed distributions

SMOTE applied to balance the target classes

4️⃣ Model Training

Trained the following models:

Model	Accuracy	Recall (Approved)	Recall (Not Approved)	Macro F1
Logistic Regression	0.839	0.91	0.71	0.82
Random Forest	0.851	0.93	0.71	0.83
XGBoost	0.851	0.93	0.71	0.83
Best Model:

✔ Random Forest / XGBoost (both performed almost the same)

🤖 Final Prediction Function

A custom function was built to:

Accept new customer data

Apply the same encoding/scaling

Predict loan approval using the best model

Return Approval Probability + Decision

📝 Model Conclusion

The ML models demonstrate strong predictive performance with 85% accuracy.
XGBoost and Random Forest handle complex relationships effectively and generalize well on unseen data.

The system can assist financial institutions in:

Faster loan processing

Detecting risky applicants

Improving credit decision accuracy

Reducing manual workload
