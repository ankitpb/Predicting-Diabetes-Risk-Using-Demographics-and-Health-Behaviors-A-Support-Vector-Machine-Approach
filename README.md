# Predicting Diabetes Risk Using Support Vector Machines (SVM)

## Overview
This project explores the use of Support Vector Machines (SVMs) to predict diabetes risk based on demographic and health behavior variables from the 2022 NHIS dataset.  
The final deliverables include Python code, a poster, and plots demonstrating model performance.

## Methodology
- Selected 10 health and demographic variables from the NHIS dataset.
- Scaled features using StandardScaler.
- Applied SMOTE to balance diabetic and non-diabetic cases.
- Trained Linear, RBF, and Polynomial SVMs.
- Performed GridSearchCV to tune hyperparameters.
- Visualized decision boundaries using two strong predictors (Age, BMI).
- Evaluated models based on Accuracy, Recall, and ROC-AUC.

## Results
- Linear SVM achieved the highest ROC-AUC (~0.80).
- Age and BMI were strong predictors of diabetes.
- Decision boundary and ROC curve plots highlight model strengths and weaknesses.

## Citation
Dataset:  
> Lynn A. Blewett et al. IPUMS Health Surveys: NHIS, Version 7.4 [dataset]. IPUMS, 2024. https://doi.org/10.18128/D070.V7.4
