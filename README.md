# Obesity_risk_analysis_ML
This project uses XGBClassifier for multi-class classification, with a full ColumnTransformer pipeline for robust preprocessing (scaling, one-hot, ordinal) and BMI feature engineering.

# Kaggle Competition: Obesity Risk Prediction

This repository contains the complete notebook and solution for the **AIT 511 Course Project 1: Obesity Risk** competition hosted on Kaggle.

The entire workflow, from data preprocessing and feature engineering to model training (using XGBClassifier) and submission, is contained within the notebook.

## 🎯 Competition Link

This notebook was built specifically for this competition. You can find the competition details and leaderboard here:
[https://www.kaggle.com/competitions/ait-511-course-project-1-obesity-risk/leaderboard](https://www.kaggle.com/competitions/ait-511-course-project-1-obesity-risk/leaderboard)

## 🚀 How to Run

1.  **Download the Data:**
    You must download the `train.csv` and `test.csv` files directly from the Kaggle competition's "Data" tab (link above).

2.  **Place Data:**
    Place the downloaded `train.csv` and `test.csv` files in the same directory as the main notebook.

3.  **Run Notebook:**
    Open and run the notebook (`Obesity_risk_analysis.ipynb`) in an environment like Jupyter Lab or VS Code. The notebook will handle all preprocessing and will generate a `submission.csv` file, which you can then upload to Kaggle.