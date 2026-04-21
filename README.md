# Loan Prediction System

A machine learning project for predicting loan approval using applicant and financial details.

## Repository Contents

- `credit_wise.ipynb` — main notebook for data analysis, preprocessing, model training, and evaluation  
- `loan_approval_data.csv` — dataset used in the notebook

## Dataset

The dataset includes applicant profile and financial features such as:

- Applicant and co-applicant income
- Employment status
- Age, marital status, dependents
- Credit score, existing loans, DTI ratio
- Savings, collateral value
- Loan amount, loan term, loan purpose
- Property area, education level, gender, employer category

Target variable: `Loan_Approved` (`Yes`/`No`)

## What the Notebook Does

1. Loads and inspects the dataset  
2. Handles missing values  
3. Encodes categorical features  
4. Splits data into train/test sets  
5. Scales features where needed  
6. Trains and evaluates multiple models

## Models Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Gaussian Naive Bayes  

## Observed Accuracy (from notebook runs)

- Logistic Regression: ~0.865 to 0.875  
- KNN: ~0.755 to 0.760  
- Gaussian Naive Bayes: ~0.865  

## Requirements

Install Python packages used in the notebook:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

## How to Run

1. Open the project folder
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
