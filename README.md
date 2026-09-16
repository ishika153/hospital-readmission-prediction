# Hospital Readmission Prediction using Logistic Regression

## Overview

This project predicts whether a patient will be readmitted to the hospital
within 30 days of discharge using Logistic Regression with L2 regularization.

## Dataset

**Diabetes 130-US Hospitals for Years 1999-2008**

The dataset contains hospital patient records, including diagnosis codes,
laboratory results, and prior hospital visits.

The original dataset is available from the UCI Machine Learning Repository.

## Techniques Used

- Data Cleaning
- Missing Value Handling
- Feature Selection
- One-Hot Encoding
- Feature Scaling
- Train-Test Split
- Logistic Regression
- L2 Regularization
- ROC-AUC Evaluation
- Confusion Matrix
- False Positive / False Negative Analysis

## Target

The original `readmitted` variable was converted into a binary target:

- `<30` → 1 (readmitted within 30 days)
- `>30` → 0
- `NO` → 0

## Results

ROC-AUC: **[ENTER YOUR ROC-AUC SCORE]**

## Clinical Considerations

False negatives may be clinically important because a patient at risk of
readmission could be incorrectly classified as low-risk. False positives
may lead to additional healthcare resource utilization.

## Files

- `Hospital_Readmission_Prediction.ipynb` — Complete Jupyter/Colab notebook
- `README.md` — Project description
- `hospital_readmission_predictions.csv` — Model predictions

## Dataset Source

UCI Machine Learning Repository
