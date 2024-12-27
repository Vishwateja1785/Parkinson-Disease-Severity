# Quantitative Assessment of Parkinson's Disease Severity

## Project Overview

This project focuses on developing machine learning models to identify factors influencing Parkinson's disease severity. By analyzing biomedical voice measurements and other clinical data, we aim to predict the Unified Parkinson's Disease Rating Scale (UPDRS) scores, which are commonly used to assess the progression of Parkinson's disease symptoms.

## Key Features

- Utilization of multiple regression models and machine learning algorithms
- Analysis of biomedical voice measurements as potential predictors of disease severity
- Investigation of gender effects on the relationship between voice measurements and UPDRS scores
- Dimensionality reduction using Principal Component Analysis (PCA)
- Feature selection and regularization with Lasso regression

## Data

The dataset used in this project includes:
- 5,875 voice recordings from 42 individuals with early-stage Parkinson's disease
- 22 variables including patient demographics, UPDRS scores, and various biomedical voice measurements

## Methods

1. Multiple Linear Regression
2. Support Vector Machines (SVM)
3. Decision Trees
4. Principal Component Analysis (PCA)
5. Lasso Regression

## Key Findings

- Certain biomedical voice measures (Jitter, Shimmer, HNR, RPDE, DFA, PPE) significantly influence total UPDRS scores
- Gender interactions play a role in the relationship between voice measurements and disease severity
- PCA effectively reduces model complexity while maintaining predictive accuracy
