# Maternal Health Risk Prediction | Data Science Project

Predictive Modeling & Analysis using Secondary Data from Kaggle

## Problem Statement

The objective of this project is to build and evaluate machine learning models to predict the likelihood of an individual being diagnosed with maternal health risks. The prediction is based on a comprehensive secondary dataset sourced from Kaggle, which combines lifestyle factors and clinical/medical history data (e.g., Age, SystolicBP, DiastolicBP, Blood Sugar, BodyTemp, HeartRate). This project involves data preprocessing, exploratory data analysis (EDA), and comparing multiple machine learning classification algorithms.

## Key Tasks & Objectives

1.  **Data Ingestion & Inspection:** Load the raw secondary dataset from Kaggle (`Maternal_Health_Risk_DataSet.csv`). Inspect data shape, missing values, and check for duplicated entries.
2.  **Data Preprocessing:**
    *   Encode categorical text columns (e.g., RiskLevel) using manual mapping.
    *   Separate the dataset into features (X) and the target variable (y = RiskLevel).
    *   Standardize numerical features using `StandardScaler` to ensure clinical metrics and lifestyle counts are on the same scale.
3.  **Exploratory Data Analysis (EDA):**
    *   Visualize the distribution of the target variable using a count plot.
    *   Generate a correlation heatmap to analyze relationships between clinical/lifestyle features and maternal health risk.
    *   Create boxplots to understand feature distributions across different risk levels.
4.  **Model Training & Evaluation:** Train and evaluate multiple classifiers using Accuracy, Macro Recall, Macro F1-Score, Confusion Matrix, and Classification Reports:
    *   Logistic Regression
    *   Decision Tree
    *   Random Forest
    *   Gradient Boosting Classifier
    *   Support Vector Machine
5.  **Advanced Metrics & Interpretability:**
    *   Calculate and plot the ROC-AUC curve for the best-performing model (Random Forest).
    *   Extract and visualize the top 10 most important features contributing to the model's predictions to understand which lifestyle or clinical factors drive the highest risk.

## Repository Contents

*   **predict_risk_during_pregnancy.ipynb:** The main Jupyter Notebook containing the Python codebase for data preprocessing, EDA, and predictive modeling.
*   **Maternal_Health_Risk_DataSet.csv:** The raw secondary Kaggle dataset containing clinical and lifestyle records used for the analysis.

## Author

Mahmuda Khatun  
PGD in Information Technology, IIT, University of Dhaka  
MSc in Health Informatics, Bangladesh University of Health Sciences
