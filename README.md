# Supervised Machine Learning Project

## Project Overview
This project demonstrates different Supervised Machine Learning algorithms for both Regression and Classification problems. It is organized in two parts:

**Part 1 — Concepts** (bias-variance tradeoff, overfitting/underfitting, cross validation, hyperparameter tuning, performance metrics) and

**Part 2 — Case Study** (full regression and classification pipelines on real datasets).

## Datasets

### Regression Dataset
2015 US Domestic Flights Dataset (a clean random sample of 40,000 completed, non-diverted flights, merged with an airline lookup table)
**Target Variable:** `ARRIVAL_DELAY`

### Classification Dataset
Breast Cancer Wisconsin (Diagnostic) Dataset
**Target Variable:** `diagnosis` (malignant vs benign)

## Regression Models
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor

### Evaluation Metrics
- MAE
- MSE
- RMSE
- R² Score

## Classification Models
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Techniques Used
- Data Cleaning
- Data Preprocessing
- Feature Encoding (One-Hot Encoding, Standard Scaling)
- Train-Test Split
- Cross Validation
- Hyperparameter Tuning (Grid Search)
- Model Comparison

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results
Five regression models and five classification models were trained and evaluated. Their performances were compared using evaluation metrics and visualization graphs. Cross Validation and Hyperparameter Tuning were performed for every model to improve performance.

- **Best Regression Model:** Linear Regression (Test RMSE ≈ 9.97 minutes, R² ≈ 0.923), narrowly ahead of Ridge and Lasso Regression.
- **Best Classification Model:** SVM (Accuracy ≈ 98.2%, F1 Score ≈ 0.986), closely followed by Logistic Regression and KNN.

## Author
Bilquees Ashfaq Jumani
