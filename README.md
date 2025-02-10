# Breast-Cancer-Diagnosis-using-Random-Forest


## Overview

This project implements a Random Forest Classifier to diagnose breast cancer using the Breast Cancer Wisconsin Dataset from Scikit-Learn. The model is evaluated with k-fold cross-validation, and hyperparameter tuning is performed using GridSearchCV.

## Dataset

The dataset is loaded using Scikit-Learn's built-in function:

* Features: Various attributes related to cell nuclei characteristics

* Labels: Malignant (1) or Benign (0)

## Features

* Uses Random Forest Classifier for classification

* GridSearchCV for hyperparameter tuning

* K-Fold Cross-Validation for model evaluation

* Performance metrics: Accuracy, Precision, Recall, and F1-score

Installation

Ensure you have Python and the required libraries installed:

``` pip install scikit-learn numpy ```

Usage

Run the cells in  ``` breast_cancer_rf.ipynb ```

Results

The script prints out the following performance metrics:

* Accuracy: Overall correctness of the model

* Precision: Correctly identified malignant cases

* Recall: Sensitivity of the model to malignant cases

* F1-score: Harmonic mean of precision and recall
