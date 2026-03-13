# Diabetes Logistic Regression

## Objective
Build a baseline logistic regression model to predict diabetes risk from health metrics, handling invalid zero values properly.

## Dataset
Pima Indians Diabetes dataset (~768 rows, features: pregnancies, glucose, blood pressure, insulin, BMI, etc.)

## Approach
- EDA + visualizations
- Replaced invalid zeros (e.g. glucose=0, BMI=0) with medians
- Scaled features
- Trained LogisticRegression (scikit-learn)
- 
- Key: Proper zero handling improved model stability
  
##Libraries:
Python, pandas, NumPy, scikit-learn, Matplotlib/Seaborn
