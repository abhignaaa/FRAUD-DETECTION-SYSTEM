# Fraud Detection System

## Overview

This project is aimed at building a Fraud Detection System using machine learning, specifically employing a Random Forest Classifier. The system analyzes a credit card transaction dataset to identify potentially fraudulent activities.

## Files and Structure

- `fraud_detection_system.py`: Python script containing the code for the fraud detection system.
- `creditcarddata.csv`: Dataset file containing credit card transaction data.

## Libraries Used

- `numpy`: For numerical operations.
- `matplotlib.pyplot`: For data visualization.
- `pandas`: For data manipulation and analysis.
- `seaborn`: For statistical data visualization.
- `scikit-learn`: For machine learning tasks.
- `plotly.express`: For creating interactive visualizations.

## Data Exploration and Visualization

The script performs the following tasks:

1. Loads the dataset from the specified file path.
2. Checks for null values in the dataset.
3. Describes the dataset and visualizes the relationship between fraud transactions and transaction amounts using various plots.

## Imbalance Analysis

Analyzes the imbalance in the dataset and prints information about fraud cases and valid transactions. It also provides details about the amount of fraudulent transactions compared to normal transactions.

## Correlation Matrix Heatmap

Generates a heatmap visualizing the correlation matrix of the dataset.

## Data Preprocessing

1. Separates the dataset into input parameters (`X`) and output values (`Y`).
2. Splits the data into training and testing sets.

## Model Building - Random Forest

1. Builds a Random Forest model using scikit-learn.
2. Evaluates the model on the training and testing sets.
3. Computes metrics such as precision, recall, F1-score, Matthews correlation coefficient, and accuracy.

## Confusion Matrix

Displays a confusion matrix for the model's predictions on the test set, providing insights into the model's performance.

## How to Run

1. Make sure to have the required libraries installed (`numpy`, `matplotlib`, `pandas`, `seaborn`, `scikit-learn`, `plotly`).
2. Run the `fraud_detection_system.py` script.

Feel free to modify the code or dataset path as needed for your specific use case.

## Results
- The model's performance metrics and the confusion matrix are presented.

