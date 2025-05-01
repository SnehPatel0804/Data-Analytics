Breast Cancer Diagnosis - Classification & Regression Analysis

📋Project Overview

This project performs exploratory data analysis (EDA), feature selection, model training, and evaluation using both classification and regression techniques on a breast cancer dataset. The goal is to predict cancer diagnosis (Malignant or Benign) using various machine learning models.

🛠️ Technologies Used

. Programming Language: Python 

. Data Handling: pandas, numpy

. Visualization: matplotlib, seaborn

. Machine Learning:

- scikit-learn (Linear Regression, Logistic Regression, Random Forest, KNN)

- XGBoost (for regression and classification)

. Other Tools: Jupyter Notebook / Google Colab

📂 Dataset

. File: data.csv

. Description: Contains various features extracted from digitized images of a breast mass.

. Target variable: diagnosis (M = malignant, B = benign)

📊 Project Structure

1) Data Exploration

. Dataset preview, shape, and column info

. Missing values check

2) Exploratory Data Analysis (EDA)

. Correlation matrix heatmap

. Histogram plots for feature distributions

3) Feature Selection

. Feature importance via Random Forest

4) Model Training

. Regression Models

- Linear Regression

- Random Forest Regressor

- XGBoost Regressor

. Classification Models

- K-Nearest Neighbors (KNN)

- Logistic Regression

- Random Forest Classifier

- XGBoost Classifier

5) Model Evaluation

. Regression: R² Score, MAE, MSE

. Classification: Accuracy

6) Visualizations

. Bar charts for scores

. Confusion matrices

. ROC curves (AUC)

. Actual vs Predicted scatter plots

. Residual distribution

. Feature importance

7) Final Comparison

Combined chart comparing classification and regression model performances

✅ Requirements
Make sure to install the following Python libraries:

pip install pandas matplotlib seaborn scikit-learn xgboost


📌 Notes

The target column (diagnosis) is encoded for use in both regression and classification.

Both model categories are used for learning and comparison purposes.

Feature importances and ROC curves help in model interpretability.

📈 Results Summary

Best Classification Model: (based on accuracy)

Best Regression Model: (based on R² score)

Refer to the final visualization for performance comparison.