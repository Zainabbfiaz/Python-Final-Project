# Python-Final-Project
A machine learning project that classifies mushrooms as edible or poisonous using Python and classification algorithms.
# Mushroom Classification Project

## Project Overview

This project develops a machine learning model to classify mushrooms as edible or poisonous based on their physical characteristics. The workflow includes data preprocessing, model training, and performance evaluation.

## Data

* Source: UCI Mushroom Dataset (via Kaggle)
* Features include: cap shape, cap color, odor, gill size, gill color, stalk characteristics, habitat
* Target variable: Edible (e) vs Poisonous (p)

## Data Preprocessing

* Replaced missing values (?) with "unknown"
* Removed columns with no variation
* Encoded categorical variables into numerical format
* Split dataset into training and testing sets (80/20)

## Model

* Algorithm: Decision Tree Classifier
* No feature scaling required
* Trained on 80% of the data and tested on 20%

## Results

* Achieved 100% accuracy on the test set
* No false positives or false negatives in the confusion matrix
* Model correctly classified all mushrooms in the test data

## Model Insights

* Gill color was the most important feature in classification
* The model relied on a small number of highly informative features

## Data Visualization

* Class distribution (edible vs poisonous)
* Feature vs target comparisons
* Feature importance plot

## Key Takeaway

A Decision Tree model is sufficient to accurately classify mushrooms in this dataset due to strong feature separability.

