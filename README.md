# Loan-Approval-Prediction

## Overview
This project aims to predict loan approval outcomes for bank customers based on their personal and financial information. By analyzing various factors such as the number of dependents, education level, employment status, annual income, loan amount, loan term, CIBIL score, and asset values, we build a model that can forecast the likelihood of a loan being approved or rejected.

## Dataset
The dataset used contains several attributes of the customers' information, including:
- Number of dependents
- Education level
- Employment status
- Annual income
- Loan amount and term
- CIBIL score
- Asset values (residential, commercial, luxury, and bank)

## Data Preprocessing
The dataset was first cleaned to remove any unnecessary columns. Missing values were checked, and feature engineering was applied to categorize assets into movable and immovable assets.

## Exploratory Data Analysis (EDA)
Visualizations were created to understand the distribution and impact of different variables on the loan approval process.

Assets were categorized as 'movable' or 'immovable' to aid in understanding the financial background of the customers better.

## Model Training
Two models were trained to predict loan approval status:
1. Decision Tree Classifier
2. Random Forest Classifier

## Model Evaluation
The models were evaluated based on their accuracy and error metrics, with the Decision Tree Classifier performing slightly better than the Random Forest Classifier.

## Conclusion
The Decision Tree Classifier is a promising tool for banks and financial institutions to predict loan approvals efficiently.

## Usage
To run this project, you will need to have Python installed along with the following libraries:
- NumPy
- Matplotlib
- Pandas
- Seaborn
- scikit-learn
