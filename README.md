# MLP-Classifier-on-Iris-Dataset

## Overview

This repository contains code for training a Multi-Layer Perceptron (MLP) classifier on the Iris dataset using scikit-learn. The code demonstrates how to split the data into training and testing sets, train the model, evaluate its accuracy on the test set, and perform cross-validation for a more robust assessment.

## Files

- `mlp_classifier_iris.py`: Python script containing the code for training the MLP classifier.
- `README.md`: This file providing information about the project.

## Results
The script outputs the accuracy of the MLP classifier on the test set and cross-validation scores.

Training Accuracy
Test Accuracy
Cross-validation scores

## Parameters
MLPClassifier:

Hidden Layer Sizes: (10, 10)

Maximum Iterations: 1000

Train-Test Split: 80% training, 20% testing

## Potential Improvements
Experiment with different hyperparameters for the MLPClassifier.
Evaluate the model on a larger and more diverse dataset.
Address overfitting concerns by adjusting the model complexity.

## Acknowledgments
The code in this repository is based on scikit-learn's MLPClassifier and Iris dataset.

## Dependencies
- scikit-learn
- pandas

Install dependencies using:

```bash
pip install scikit-learn pandas
