# Diabetes Progression Prediction with Linear Regression

![Regression Analysis Plot](regression_analysis.png)

## Project Overview
This project implements simple and multiple linear regression to predict diabetes progression based on biological factors. Using the Diabetes Dataset from scikit-learn, we analyze relationships between features like BMI, blood pressure, and blood serum measurements with disease progression.

## Dataset Description
*Source:* scikit-learn's load_diabetes()  
*Samples:* 442 patients  
*Features:* 10 numerical medical predictors  
*Target:* Quantitative measure of disease progression after 1 year  

Key Features:
- bmi: Body Mass Index
- bp: Average Blood Pressure
- s1-s6: Blood serum measurements

## Implementation
### Dependencies
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
