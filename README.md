# 📊 Customer Churn Prediction using Machine Learning

This project predicts whether a customer will churn (leave the service) using machine learning techniques in Python. The dataset contains customer demographics, account details, and service usage patterns. The goal is to build a reliable classification model that helps identify customers at risk of leaving.

## 🚀 Project Overview

The workflow includes:

Data loading and preprocessing

Converting column names to snake_case

Handling missing and inconsistent values

Encoding categorical features (LabelEncoder + OneHotEncoder)

Feature scaling using StandardScaler

Model training using Logistic Regression & Random Forest

Evaluating performance using accuracy, precision, recall & confusion matrix

Extracting feature importance

Saving the trained model using joblib

## 🧹 Data Cleaning & Preprocessing

Converted column names into snake_case for better readability.

Cleaned the "total_charges" column by coercing invalid values to NaN and filling with the median.

Applied LabelEncoder on binary Yes/No columns.

Used OneHotEncoder for multi-class categorical variables.

Scaled numerical features to improve model performance.

## 🧠 Machine Learning Models Used

Logistic Regression (baseline model)

Random Forest Classifier (feature importance & improved performance)

Random Forest also provides .feature_importances_ for identifying key factors influencing churn.

## 📈 Results

Evaluated models using:
✔ Accuracy
✔ Precision
✔ Recall
✔ Confusion Matrix

Identified top features contributing to churn risk using RandomForest.



## 📁 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Joblib


## 👨‍💻 Author

Aakash — Data Analyst 
Feel free to fork, star ⭐, or contribute!
