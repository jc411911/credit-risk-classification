 # Credit Risk Classification
Module 20 Joe Almendarez

This project aims to classify credit risk using machine learning models. The primary focus is on predicting whether a loan is high-risk or healthy based on various financial features.

## Project Structure

- `credit_risk_classification.ipynb`: Jupyter notebook containing the data analysis, model training, and evaluation.
- `lending_data.csv`: Dataset used for training and testing the machine learning models.

## Overview

The notebook follows these main steps:

1. **Data Preparation**:
   - Load the dataset from `lending_data.csv`.
   - Separate the data into features (`X`) and labels (`y`).

2. **Data Splitting**:
   - Split the data into training and testing sets using `train_test_split`.

3. **Model Training**:
   - Train a logistic regression model using the training data.

4. **Model Evaluation**:
   - Evaluate the model's performance using a confusion matrix and classification report.
   - Calculate accuracy, precision, recall, and F1-score for both high-risk and healthy loans.

## Results

The logistic regression model performs well in predicting both high-risk and healthy loans, with high precision, recall, and overall accuracy.
