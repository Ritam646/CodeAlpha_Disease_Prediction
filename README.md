# CodeAlpha Disease Prediction
## Overview
Predicts diseases (Heart, Diabetes, Breast Cancer) using SVM, Logistic Regression, Random Forest, and XGBoost.
## Dataset
- Sources: UCI ML Repository, Kaggle
- Heart: age, sex, cp, trestbps, chol, etc.
- Diabetes: preg, glucose, bp, skin, etc.
- Breast Cancer: clump_thickness, uniform_cell_size, etc.
## Setup
- Run in Google Colab
- Install: `pip install pandas sklearn seaborn xgboost kaggle`
## Results
- Heart: Random Forest 0.883
- Diabetes: Random Forest 0.760
- Breast Cancer: SVM 0.964
## Files
- CodeAlpha_Disease_Prediction.ipynb: Main code
- *_confusion_matrix.png: Confusion matrices
- accuracy_comparison.png: Accuracy plot
- heart_model.pkl: Best model for Heart
- diabetes_model.pkl: Best model for Diabetes
- breast_model.pkl: Best model for Breast Cancer
