🏦 Need Bank Loan or Not
📘 Project Overview

This project predicts whether a person is eligible for a bank loan based on their personal and financial details.
Users provide information such as income, credit history, loan amount, and other factors, and the trained model predicts if the applicant is likely to be approved or not.

The model is deployed as a web application on Render, allowing users to test real-time loan eligibility predictions through an easy-to-use interface.



🚀 Key Features

Predicts loan eligibility based on user input

Built using multiple machine learning models

Deployed as an interactive web app using Flask on Render

Supports real-time prediction



🧠 Machine Learning Models Used

The project compares several ML algorithms to identify the best-performing one:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

XGBoost Classifier

AdaBoost Classifier

The model achieving the highest accuracy and generalization score was chosen for deployment.



📊 Dataset

Source: Kaggle (Loan Prediction Dataset)

Description:
The dataset contains applicant information such as:

Gender, Marital Status, Education, Dependents

Applicant and Coapplicant Income

Loan Amount, Loan Term

Credit History

Property Area

Loan Status (Target variable)



⚙️ Tech Stack

Language: Python 🐍

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

Model Deployment: Flask + Render

Environment: Jupyter Notebook



🧩 Project Workflow

Data Preprocessing:

Handled missing values

Encoded categorical features

Scaled numerical data

Exploratory Data Analysis (EDA):

Visualized correlations between income, loan amount, and loan status

Identified key features influencing approval

Model Training and Evaluation:

Trained multiple ML models

Evaluated performance using accuracy, precision, recall, and F1-score

Selected the best-performing model for deployment

Deployment:

Created a Flask web interface

Integrated the model for real-time prediction

Deployed on Render for public access


🌐 Live Demo

👉https://customer-loan-conversion-prediction.onrender.com/
