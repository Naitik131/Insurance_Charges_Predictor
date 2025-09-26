# Insurance_Charges_Predictor
# Medical Insurance Charges Prediction

## Overview
Predict medical insurance charges using machine learning. The project demonstrates a full ML workflow: data loading, cleaning, feature engineering, scaling, model training (Linear Regression, XGBoost), evaluation, and interpretation.

## Dataset
Dataset used: `medical.csv` (columns include age, sex, bmi, children, smoker, region, charges).

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook

## What I did
1. Data cleaning and encoding of categorical variables (sex, smoker, region).  
2. Train-test split and feature scaling (StandardScaler).  
3. Trained and compared models:
   - Linear Regression (baseline)
   - XGBoost Regressor  
4. Evaluated models using R² and MSE

## Results
- Best model: XGBoost
- XGBoost R² (test): **~0.86**
- Linear Regression R² (test): **~0.76**
- Visuals: correlation heatmap

## How to run
1. Clone repo  
2. Install dependencies: `pip install -r requirements.txt`  
3. Open `notebooks/medical_insurance.ipynb` in Jupyter or run in Kaggle

