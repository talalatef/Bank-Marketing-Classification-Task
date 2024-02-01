# Bank_Marketing_Classification_Task

## Overview

The main goal is to develop a predictive model to determine whether a client will subscribe ('yes') or not ('no') to the term deposit offered by the bank.

## Phases Of Project

### 1. Business Understanding

- **Context:**
  - The dataset focuses on `direct marketing campaigns` conducted by a Portuguese banking institution. These campaigns involve phone calls made to clients with the aim of promoting a term deposit.

- **Objective:**
  - Predict whether a client will subscribe ('yes') or not ('no') to a term deposit.

### 2. Analytic Approach

- **Classification Goal:**
  - Employ machine learning classification algorithms for predicting binary outcomes.

- **Potential Models:**
  - Logistic regression, decision trees, random forests, and support vector machines.

### 3. Data Requirement

- **Key Variables:**
  - Identification of essential variables like client demographics, campaign details, and the outcome variable.

- **Supplementary Data:**
  - Consideration of additional information such as economic indicators or market trends during the campaign period.

### 4. Data Collection

- **Source:**
  - Data collected from the Kaggle website.

- **Quality Check:**
  - Assessment of data quality, completeness, and handling of missing values.

- **Additional Data:**
  - Acquisition of supplementary data if necessary.

### 5. Data Understanding

- **Features:**
  - Description of key features including client data, contact details, and other attributes.

- **Impact on Classification:**
  - Analysis of how each feature can affect the classification of the target variable.

### 6. Data Preparation

- **EDA (Exploratory Data Analysis):**
  - Univariate, bivariate, and multivariate analyses for understanding and preparing the data.

- **Encoding and Normalization:**
  - One-hot encoding of categorical features and normalization of numeric features.

### 7. Modeling

- **Model Selection:**
  - Evaluation of different classification models including Logistic Regression, Decision Trees, and Random Forests.

- **Optimization:**
  - Hyperparameter tuning using the Optuna library.

### 8. Evaluation

- **Model Evaluation:**
  - Assessment of model performance using accuracy, classification report, and confusion matrix.

### 9. Model Selection

- **Chosen Model:**
  - Selection of the Logistic Regression model based on its high accuracy and suitability for the task.

