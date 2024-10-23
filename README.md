# Credit-Risk-Analysis-for-Extending-Bank-Loans
# Overview
This project aims to predict the likelihood of loan default using machine learning techniques, helping banks make informed decisions about extending loans. By analyzing customer financial data, the model identifies key factors that influence credit risk.

# Project Structure
### Data Preprocessing: 
Handled missing values, encoded categorical variables, and created features such as debt-to-income ratio and total debt.
### Models: Implemented two machine learning models:
Logistic Regression for baseline classification.
LightGBM for high-performance classification with hyperparameter tuning.
### Hyperparameter Tuning: 
Used Optuna to optimize LightGBM's hyperparameters, improving model performance.
### Regularization: 
Applied GridSearchCV to further fine-tune the model with additional regularization parameters.
### Evaluation: 
The model's performance was evaluated using accuracy, confusion matrix, classification report, and ROC-AUC score.

