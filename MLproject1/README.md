# Project 1: Income Classification with Decision Trees & k-NN

## Overview

The purpose of this project is to explore and compare several classification algorithms—ranging from simple baselines to more sophisticated 
models—on a real-world income prediction task. It serves as a hands-on introduction to core machine learning techniques such as model implementation, 
cross-validation, hyperparameter tuning, and performance evaluation using accuracy and F1 scores.

The dataset used is a **subset of the UCI Adult Income dataset**, also known as the "Census Income" dataset. Each record corresponds to an individual 
from the 1994 U.S. Census and includes attributes such as age, education level, marital status, and hours worked per week. The task is to predict whether 
an individual's income exceeds \$50,000/year based on these features. The dataset is commonly used for benchmarking classification algorithms due to its 
mix of categorical and continuous features and moderate class imbalance.

---

## Concepts Covered

- Custom implementation of basic classifiers:
  - `MajorityVoteClassifier`
  - `RandomClassifier`
- Use of scikit-learn models:
  - Decision Tree Classifier
  - k-Nearest Neighbors (k-NN)
- Performance evaluation with:
  - Accuracy
  - F1 Score
  - Stratified cross-validation
  - Learning curves
- Hyperparameter tuning:
  - Selecting best `k` (for k-NN) and tree `max_depth` (for Decision Trees)
- Visualization:
  - Histograms
  - Validation error curves
  - Learning curves

---

## Files
| `adult_subsample.csv` | Preprocessed version of the UCI Adult Income dataset |
---

