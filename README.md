# Loan Default Risk Prediction

## Overview
This project focuses on predicting loan default risk using machine learning techniques.
The objective is to help financial institutions identify high-risk borrowers and make
data-driven lending decisions.

## Dataset
The dataset contains borrower demographic, financial, and loan-related information,
including income, loan amount, interest rate, employment length, and credit history.
The target variable indicates whether a borrower defaulted on the loan.

## Approach
- Performed exploratory data analysis (EDA) to understand borrower characteristics and default patterns.
- Cleaned data by handling missing values and encoding categorical variables.
- Built a Logistic Regression model as a baseline.
- Trained a Random Forest model to capture non-linear risk patterns.
- Evaluated models using precision, recall, F1-score, and ROC-AUC.
- Analyzed feature importance to identify key default risk drivers.

## Project Structure

Loan-Default-Risk/
│── data/          # Dataset files
│── notebooks/     # Jupyter notebook for EDA and modeling
│── README.md
│── requirements.txt
│──LICENSE
│──.gitignore

## Key Insights
- Loan interest rate, loan amount, and borrower income are strong predictors of default risk.
- Borrowers with higher interest rates and lower income exhibit higher default probability.
- Random Forest outperformed Logistic Regression in capturing complex risk patterns.

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Git, GitHub
