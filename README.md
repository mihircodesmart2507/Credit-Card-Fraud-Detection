# Credit-Card-Fraud-Detection:

This project aims to detect fraudulent credit card transactions using supervised machine learning models. It uses a real-world dataset with anonymized features and handles imbalanced data to build accurate and reliable classification models. 

# Table of Contents:

-Overview
-Dataset
-Technologies Used
-Data Preprocessing
-Modeling
-Evaluation Metrics
-Results
-Conclusion       

# Overview 
Credit card fraud is a major issue in the financial sector. In this project, various machine learning algorithms were used to identify fraudulent transactions based on a dataset of credit card usage. The goal was to accurately detect fraud while handling the extreme class imbalance in the data. 

# Dataset
You can download the dataset from [this link](https://www.kaggle.com/mlg-ulb/creditcardfraud).  

# Technologies Used 

-Python
-Pandas, NumPy
-Scikit-learn
-Seaborn, Matplotlib
-SMOTE (for balancing the dataset)  

# Data Preprocessing

- Verified data shape, types, and class distribution
- No missing values detected in the dataset
- Scaled numerical features (`Time`, `Amount`) using `Standardscalar`
- Applied SMOTE to handle extreme class imbalance
- Split the dataset into training and test sets for model evaluation

# Modeling
-Implemented the following ML models:
-Logistic Regression
-Random Forest Classifier  

# Evaluation Metrics
Used standard classification metrics due to class imbalance:

-Precision
-Recall
-F1 Score
-Confusion Matrix
-ROC-AUC Curve  

# Results

-Models were evaluated for their ability to minimize false negatives (i.e., missed frauds).
-Random Forest showed strong performance in terms of recall and precision.
-SMOTE helped improve model fairness for minority (fraud) class.  

# Conclusion 

Machine learning can effectively identify fraudulent transactions with the right preprocessing and evaluation strategies. Handling class imbalance is crucial to building a trustworthy fraud detection system. 

# Author
Mihir Aryan Mishra 
[Linkedln](https://www.linkedin.com/in/mihiraryan25/) 
[GitHub](https://github.com/mihircodesmart2507)


