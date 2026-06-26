# Customer Churn Prediction and Customer Segmentation

## About the Project

Customer churn is a major challenge for telecom companies because losing existing customers directly affects business revenue.

This project predicts whether a customer is likely to churn using Machine Learning. It also groups customers with similar behavior using K-Means clustering. The goal is to help businesses identify high-risk customers and make better retention decisions.

---

## Problem Statement

Companies often do not know which customers are planning to leave.

Without this information, businesses lose customers and revenue.

---

## Solution

A Random Forest model was built to predict customer churn.

GridSearchCV was used to optimize the model and improve its performance.

K-Means clustering was used to group customers based on their behavior.

---

## Dataset

* Telco Customer Churn Dataset
* Target Variable: **Churn**
* Features include customer demographics, services, contract type, tenure, monthly charges, and total charges.

---

## Project Workflow

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Feature Encoding
* Train-Test Split
* Random Forest Model
* Hyperparameter Tuning using GridSearchCV
* Model Evaluation
* Customer Segmentation using K-Means

---

## Model Performance

### Random Forest

* Accuracy: **78.28%**
* Recall: **74.75%**

### Random Forest + GridSearchCV

* Accuracy: **74.52%**
* Recall: **82.00%**

GridSearchCV improved the recall score, which is important for churn prediction because identifying customers who are likely to leave is the main objective.

---

## Technologies
*
 Python
 Pandas
 NumPy
 Matplotlib
 Seaborn
 Scikit-learn
 *
---
## What I learrn

* Customer Churn Prediction using Random Forest
* Hyperparameter Tuning using GridSearchCV
* Feature Importance Analysis
* Cross Validation
* ROC Curve
* Customer Segmentation using K-Means
* Model Performance Comparison

---

## Results

* Built a customer churn prediction model.
* Compared the performance of Random Forest and GridSearchCV.
* Improved recall using hyperparameter tuning.
* Grouped customers into different segments using K-Means clustering.

---


## Author

**Ishika**
