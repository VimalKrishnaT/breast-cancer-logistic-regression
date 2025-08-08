# Breast Cancer Classification using Logistic Regression

## Project Overview
This project builds a binary classifier using **Logistic Regression** to predict breast cancer diagnosis (Benign vs Malignant) based on the Breast Cancer Wisconsin dataset.

We implement the full pipeline including:
- Loading and preprocessing the dataset
- Train/test split and feature scaling
- Model training with logistic regression
- Evaluation using confusion matrix, precision, recall, ROC-AUC, and classification report
- ROC curve visualization
- Decision threshold tuning
- Explanation and visualization of the sigmoid function used in logistic regression

## Dataset
The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset** which contains features computed from digitized images of breast masses.  
The target variable `'diagnosis'` has two classes:
- B: Benign (mapped to 0)
- M: Malignant (mapped to 1)

## Installation
Make sure you have the following Python libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib

You can install them using pip:
pip install pandas numpy scikit-learn matplotlib

## Usage

1. Place your dataset CSV file (e.g., `data.csv`) in the repository folder or provide a path in the script.
2. Update the `dataset_path` variable in the Python script to point to your dataset file.
3. Run the Python script `logistic_regression_breast_cancer.py` (or use a Jupyter notebook if preferred).

## Files
- `LogicRegression.ipynb`: Jupyter notebook containing the step-by-step implementation of logistic regression classification on the dataset.
- `data.csv`: Breast Cancer Wisconsin dataset file used for training and evaluation.
- `README.md`: This file with project overview, instructions, and details.

## Evaluation Metrics Explained

- **Confusion Matrix**: Visualizes true vs predicted labels, showing TP, FN, FP, TN.
- **Precision**: Proportion of true positives among positive predictions.
- **Recall**: Proportion of true positives among actual positives.
- **ROC-AUC**: Area under the ROC curve; a performance measurement for classification.

## Threshold Tuning and Sigmoid Function

The script also allows testing of custom decision thresholds besides the default 0.5, to balance precision and recall as per use case.  
The sigmoid function is visualized and explained as the function mapping linear outputs to probabilities in logistic regression.

