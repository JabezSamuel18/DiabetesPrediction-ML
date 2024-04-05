# Diabetes Prediction using Machine Learning

## Introduction

Welcome to the Diabetes Prediction project! This repository contains code and documentation for building machine learning models to predict whether patients have diabetes based on certain diagnostic measurements.

### Objective

The objective of this project is to accurately predict whether patients in the dataset have diabetes or not. This is achieved by leveraging various machine learning algorithms and techniques such as feature engineering, one-hot encoding, and model tuning.

### Dataset

The dataset used in this project is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It consists of several medical predictor variables and one target variable, Outcome, which indicates whether a patient has diabetes or not. The predictor variables include:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

All patients in the dataset are females at least 21 years old of Pima Indian heritage.

### Project Structure

The project is structured as follows:

- **Exploratory Data Analysis (EDA):** The structural data of the dataset is checked, variable types are examined, and descriptive statistics are analyzed.
- **Data Preprocessing:** Missing values are handled, outliers are detected and removed, and feature scaling is applied.
- **Model Building:** Various machine learning models such as Logistic Regression, KNN, SVM, CART, Random Forests, XGBoost, and LightGBM are implemented. Cross-validation scores are calculated to evaluate model performance.
- **Model Tuning:** Hyperparameter optimization is performed for Random Forests, XGBoost, and LightGBM to improve model performance.
