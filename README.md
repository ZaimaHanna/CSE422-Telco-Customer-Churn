# Telco Customer Churn Prediction

## 1. Introduction

This project focuses on predicting customer churn in the telecommunications industry using machine learning. The goal is to identify customers who are likely to leave the service and understand the factors associated with churn.

**Dataset:** Telco Customer Churn Dataset — 7,043 customer records and 21 columns.

## 2. Project Objective

* Analyze customer data and identify churn patterns.
* Clean and preprocess the dataset.
* Build and compare machine learning models for churn prediction.
* Evaluate model performance using multiple metrics.
* Segment customers using K-Means clustering.
* Predict churn for new customers.

## 3. Data Preprocessing

The dataset was cleaned and prepared by:

* Handling missing/blank `TotalCharges` values.
* Converting categorical variables using one-hot encoding.
* Standardizing numerical features.
* Removing the `customerID` identifier.
* Splitting the data into 80% training and 20% testing sets.

## 4. Machine Learning Models

The following models were developed and compared:

* **Decision Tree**
* **Logistic Regression**
* **Neural Network (MLP)**

## 5. Customer Segmentation

K-Means clustering was used to identify natural customer groups without using the churn label.

## 6. Key Findings

* Month-to-month customers have a much higher churn rate than long-term contract customers.
* Lower-tenure customers are more likely to churn.
* Fiber optic customers show relatively high churn.
* Electronic-check customers have a relatively high churn rate.
* Logistic Regression performed best overall among the final models.

## 7. Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

## 8. Project Notebook

The complete project is available in:

`CSE422_Telco_Churn_Merged_clean.ipynb`

The notebook contains data analysis, preprocessing, machine learning, model evaluation, K-Means clustering, and customer churn prediction.



