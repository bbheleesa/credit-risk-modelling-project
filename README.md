# Credit Risk Modelling Project

## Overview
This project builds a credit risk model to predict borrower default using Lending Club loan data. 
A logistic regression model is used to estimate default probabilities, which are then converted into a simplified credit scoring system.

## Dataset
The dataset is derived from Lending Club loan data and includes borrower financial characteristics includes (but is not limited to):
- Loan amount
- Interest rate
- Debt-to-income ratio
- Credit grade
- Employment length
- Annual income

The original dataset that was used to create the sample is linked within the notebook. However the specific file used was in .feather format, which had to be converted to .csv, which is not shown in the notebook itself.

## Methodology
The project follows a typical credit risk modelling workflow:

1. Data Cleaning and Preprocessing
2. Feature Engineering
3. Logistic Regression Model Training
4. Model Evaluation
5. Conversion of Predicted Probabilities into Credit Scores

## Results
The model achieved an ROC AUC of 0.69. This was above the random baseline of 0.5, though below the 0.75 threshold typical of production credit models, which is expected for a logistic regression baseline on a limited feature set.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
