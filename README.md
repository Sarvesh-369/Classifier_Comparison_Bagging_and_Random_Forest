# Bagging vs. Random Forest for Classification

This repository contains the implementation of Bagging and Random Forest ensemble techniques for classification tasks. The project demonstrates the use of these techniques and includes sample data preprocessing and prediction. The primary focus is on comparing the accuracy of these ensemble methods.

## Introduction

The project focuses on classification tasks using ensemble techniques, specifically Bagging and Random Forest.
It includes the following components:

- Implementation of Bagging, an ensemble method that combines multiple base models using bootstrap samples.
- Implementation of Random Forest, an ensemble method that extends Bagging by adding feature selection.
- Data preprocessing to prepare the dataset for model training and evaluation.
- Sample predictions on a test dataset using both Bagging and Random Forest.

## Implementation Details

The repository is organized as follows:

- `classifier.py`: Implementation of Bagging and Random forrest for classification, including data preprocessing and prediction.
- `train.csv`: file is the dataset used for training the Bagging and Random Forest classifiers.
- `test.csv`: Sample test data for making predictions.

## Bagging Classifier

The Bagging classifier is implemented to create an ensemble of base models. Each base model is trained on a bootstrapped sample of the data. Bagging combines the predictions of these base models to make the final prediction.

## Random Forest Classifier

The Random Forest classifier is an extension of Bagging. It includes feature selection during training, which adds an additional level of randomness to the ensemble. Random Forest is used to make predictions on a test dataset.

## Data Preprocessing

Data preprocessing functions are included to prepare the dataset for model training. The preprocessing includes data cleaning, converting categorical values to numerical values, and splitting the data into features and labels.

## Sample Predictions

Sample predictions are made using both Bagging and Random Forest models on a test dataset. The predictions are saved in separate CSV files for comparison.