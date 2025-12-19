EMI Predict AI – Financial Risk Assessment Platform

A Machine Learning–powered system that predicts:

 emi eligibility (Eligible / Not Eligible)
 Maximum emi Amount the user can afford

This project combines Python, Scikit-Learn, Streamlit, pandas, and joblib to build an end-to-end ML application — from data cleaning to deployment.
This system evaluates a user’s financial profile and determines whether they qualify for an EMI.
It also estimates how much EMI they can safely pay based on:

Salary

Expenses

Credit score

Existing loans

Bank balance


Machine Learning Models Used
Logistic Regression – EMI Eligibility
Why used:
Works best for binary classification
Interpretable
Fast and stable
Perfect for Yes/No type outcomes

Model predicts:
Eligible or Not_Eligible
Linear Regression – EMI Amount
Why used:
Output is a continuous number
Simple, explainable
Works well after feature scaling

Model predicts:
max_monthly_emi

Household details

Loan request details
