# 💓 Heart Disease Prediction using Machine Learning

This project is focused on building a machine learning model that predicts the likelihood of heart disease in patients based on various medical attributes. It uses data preprocessing, visualization, and classification techniques to develop an accurate and interpretable model.

## 📌 Table of Contents

- [Overview]
- [Dataset]
- [Technologies Used]
- [Modeling Approach]
- [Results]

## 🧠 Overview

Heart disease is one of the leading causes of death globally. Early prediction can help reduce fatality rates by enabling timely diagnosis and treatment. This notebook explores a dataset of patient health metrics and builds a predictive model using supervised learning algorithms.

## 🗃️ Dataset

- **Source**: UCI Machine Learning Repository / Kaggle (assumed)
- **Attributes**:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol
  - Fasting Blood Sugar
  - Resting ECG
  - Max Heart Rate Achieved
  - Exercise-Induced Angina
  - ST Depression
  - Slope, Number of Major Vessels, Thal
  - **Target**: Presence or absence of heart disease

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas, NumPy - Data Handling
- Matplotlib, Seaborn - Visualization 📊
- Scikit-learn - Machine Learning Algorithms
- Classification Metrics - Accuracy, Confusion Matrix

## 📈 Modeling Approach

- **Data Cleaning**: Handled missing values, encoded categorical features.
- **Exploratory Data Analysis (EDA)**: Correlation analysis, feature distributions.
- **Modeling**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)
- **Evaluation**: Accuracy, confusion matrix, classification report.

## ✅ Results

The model with the highest accuracy was:
- Decision Tree Algorithm with 98% accuracy.

All models were tested and validated on a test split to ensure generalizability.
