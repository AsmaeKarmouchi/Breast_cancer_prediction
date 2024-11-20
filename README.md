# Breast Cancer Prediction Application

## Description

This web application predicts whether a breast tumor is benign or malignant using a pre-trained Support Vector Machine (SVM) model. 
The user-friendly interface allows inputting tumor features through a form to obtain an immediate diagnosis.

## Features

- Predicts breast cancer type (benign or malignant) based on clinical features.
- Input data is normalized using a scaler for consistency.
- Implements and evaluates four different machine learning algorithms.
- Displays accuracy comparison as a bar chart for better insights.
- User-friendly web interface built with Flask.

## Evaluation and Visualization
The model performance is compared using a bar chart, where the accuracies of the four algorithms are displayed:

- k-Nearest Neighbors (k-NN)
- Support Vector Machine (SVM)
- Logistic Regression
- Naive Bayes

## SVM Model
The SVM model was trained on the Breast Cancer Wisconsin Dataset.
 The data was preprocessed, and a scaler was used to normalize input values. 
 The svm_model.pkl file contains the saved model using the joblib library.

## Prerequisites

Before starting, ensure the following are installed on your machine:

- Python 3.x
- Flask
- NumPy
- pandas
- scikit-learn
- joblib
- Matplotlib 
- Seaborn 

## Installation

1. Clone this GitHub repository to your local machine:
   ```bash
   git clone https://github.com/AsmaeKarmouchi/Breast_cancer_prediction.git
