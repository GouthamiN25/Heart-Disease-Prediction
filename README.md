# Heart Disease Prediction Using Machine Learning

# 📌 Project Summary

This project aims to predict the presence of heart disease in patients based on multiple health parameters. The model utilizes various machine learning algorithms, including Logistic Regression, Random Forest, SVM, Gradient Boosting, and K-Nearest Neighbors (KNN). Feature selection, hyperparameter tuning, and class imbalance handling techniques were applied to enhance model performance.

# 📊 Dataset Details

The dataset used for this project contains medical attributes such as age, cholesterol levels, blood pressure, heart rate, and more.

The target variable is "target", where 1 indicates the presence of heart disease and 0 represents no heart disease.

# 🛠 Implementation Steps

Data Preprocessing:

Handled missing values (if any).

Standardized features using StandardScaler.

Feature Selection:

Used Recursive Feature Elimination (RFE) to select the most important features.

Model Training & Comparison:

Trained Logistic Regression, Random Forest, SVM, Gradient Boosting, and KNN.

Evaluated models using accuracy and ROC-AUC scores.

Hyperparameter Tuning:

Applied GridSearchCV to optimize Random Forest parameters.

Class Imbalance Handling:

Implemented SMOTE (Synthetic Minority Over-sampling Technique).

Performance Evaluation:

Used confusion matrix, classification report, and ROC-AUC curve to assess model performance.

# 📈 Results & Insights

Random Forest and Gradient Boosting models outperformed Logistic Regression and KNN.

Hyperparameter tuning improved accuracy.

SMOTE helped balance class distribution, improving recall scores.

PCA-based model did not significantly outperform selected features, confirming good initial feature selection.

