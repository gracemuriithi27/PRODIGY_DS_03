# PRODIGY_DS_03
# Internship Task Submission for Prodigy Infotech

Welcome to the repository for my internship task submission for Prodigy Infotech! In this project, I developed machine learning models to predict whether clients will subscribe to a term deposit based on demographic and behavioral data from direct marketing campaigns conducted by a Portuguese banking institution.

## Overview

The main goal of this project is to create predictive models that can assist banking institutions in targeting clients who are more likely to subscribe to term deposits. By accurately identifying potential subscribers, the institution can optimize its marketing efforts and improve campaign effectiveness.

# Decision Tree Classifier for Customer Purchase Prediction

This project builds a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The Bank Marketing dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) is used as the data source.

## Overview

- **Objective:** Predict customer purchase behavior using a decision tree.
- **Workflow:**  
  1. **Data Acquisition:** Load and inspect the Bank Marketing dataset.
  2. **Preprocessing:** Clean data and perform one-hot encoding for categorical features.
  3. **Modeling:** Train a decision tree classifier using scikit-learn.
  4. **Evaluation:** Assess model performance via accuracy, confusion matrix, and classification report.
  5. **Visualization:** Display the decision tree structure for interpretability.

## Project Structure

```plaintext
├── data/
│   └── bank.csv               # Bank Marketing dataset
├── notebooks/
│   └── Decision_Tree_Classifier.ipynb  # JupyterLab notebook with complete workflow
└── README.md                  # Project summary and instructions
