# Iris Classification

A machine learning project analyzing the classic Iris dataset using Logistic Regression to classify iris flowers based on their features.

## Overview

This project demonstrates the classification of iris flowers into three species (setosa, versicolor, and virginica) using the famous Iris dataset from scikit-learn. The analysis includes data exploration, visualization, model training, and evaluation.

## Features

- **Data Loading & Exploration**: Load the iris dataset and examine its structure and statistics
- **Data Visualization**: Create histograms and scatter plots to visualize feature distributions
- **Feature Analysis**: Analyze relationships between different flower characteristics
- **Model Development**: 
  - Simple classification rule based on petal length (90.18% accuracy)
  - Logistic Regression model (96.40% accuracy with cross-validation)
- **Model Evaluation**: Test set validation with 97.37% accuracy

## Key Visualizations

- Histograms of sepal and petal measurements
- Pair plots showing relationships between features
- Scatter plots highlighting correct and incorrect predictions

## Technical Details

- **Dataset**: 150 samples, 4 features (sepal length, sepal width, petal length, petal width)
- **Target Classes**: 3 iris species (setosa, versicolor, virginica)
- **Train/Test Split**: 75% training, 25% testing
- **Model**: Logistic Regression with 5-fold cross-validation
- **Hyperparameters**: max_iter=200, C=1

## Results

The final Logistic Regression model achieved 97.37% accuracy on the test set, misclassifying only one sample (a virginica predicted as versicolor).

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

The project is implemented in a Jupyter notebook that guides you through the data analysis, model training, and evaluation process.
