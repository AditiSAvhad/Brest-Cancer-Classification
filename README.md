# Brest-Cancer-Classification
# Breast Cancer Classification Project

## Overview
This project involves building and evaluating various machine learning models to classify breast cancer as malignant or benign using a dataset from [link to dataset if available]. The models compared include Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and K-Nearest Neighbors (KNN).

## Dataset
The dataset consists of features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. Features describe characteristics of the cell nuclei present in the image.

## Preprocessing
Removed irrelevant columns (id and Unnamed: 32).
Encoded the target variable diagnosis as 1.0 for malignant and 0.0 for benign.
Split the data into training and testing sets (70% training, 30% testing).
Standardized the feature set.

## Models
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors (KNN)

## Performance Metrics
Accuracy
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
Results
The models were evaluated and compared based on their performance on the test set.

## Dependencies
numpy
pandas
seaborn
matplotlib
scikit-learn

## Usage
1. Clone the repository.
2. Ensure all dependencies are installed.
3. Run the provided Jupyter Notebook or Python script to see the analysis and results.

## Conclusion
This project provides a comparative analysis of different classification models for breast cancer detection. It highlights the importance of model selection and preprocessing in achieving accurate predictions.

