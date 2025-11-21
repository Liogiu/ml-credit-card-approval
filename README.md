# Credit Card Approval Prediction

This project builds a machine learning model to assess the creditworthiness of applicants and predict whether a credit card request should be approved.  
The analysis includes exploratory data analysis (EDA), preprocessing, feature engineering, model comparison, and final evaluation.

## Overview

Financial institutions must evaluate credit applications based on customer financial stability, demographics, and historical behaviour.  
The goal of this project is to develop a predictive model capable of identifying reliable applicants while minimizing the risk of false approvals.

The notebook includes:
- Data exploration and variable analysis
- Data cleaning and preprocessing
- Feature encoding and scaling
- Model training and comparison
- Evaluation with appropriate classification metrics
- Business interpretation of results

## Main Steps

### 1. Exploratory Data Analysis
- Inspection of dataset structure and data types
- Identification of missing values and outliers
- Distribution analysis of key features
- Correlation analysis between variables
- Initial assessment of class imbalance in the target

### 2. Data Preprocessing
- Handling categorical and numerical features
- Encoding strategies for categorical variables
- Scaling of numerical features
- Treatment of class imbalance if required
- Splitting into training and test sets

### 3. Model Development
Multiple algorithms were tested and compared, such as:
- Logistic Regression
- Decision Trees / Random Forest
- Gradient Boosting models
- Support Vector Machines
- KNN and other baseline models

Each model was evaluated based on:
- Precision, Recall, F1-score
- Confusion matrix
- ROC curve and AUC (if included)
- Additional business-critical metrics

### 4. Model Selection and Interpretation
The best-performing model was selected based on generalization performance and the balance between false positives and false negatives.  
Feature importance or model coefficients were analyzed to understand the main drivers affecting credit approval decisions.

### 5. Evaluation
The final model was assessed using:
- Classification report on the test set
- Confusion matrix visualization
- Discussion of risks associated with misclassifications
- Interpretation of business implications

## Files in this Repository

- `ProvaML_Modelli_Algoritmi.ipynb`: full notebook containing data analysis, preprocessing, model training and evaluation.
- Dataset file (not included in the repository). If the dataset is public, please add instructions or a link to retrieve it.

## How to Run the Notebook

1. Install required libraries
Add additional packages if used in the notebook.
2. Ensure the dataset file is located in the same directory as the notebook.
3. Run the notebook
4. Execute the cells in order.

## Purpose of the Project

This project was developed as part of my Machine Learning training path and demonstrates:
- Ability to analyse and preprocess structured data
- Understanding of various classification algorithms
- Capability to compare multiple models and justify the selection
- Skill in interpreting model outputs in a business context
- Competence in building end-to-end ML pipelines

## Author

Giulio Zerilli  
Data Analyst | Python and Machine Learning


