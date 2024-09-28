# Predicting-and-Preventing-Credit-Card-Fraud-A-Machine-Learning-Approach
# Project Overview
- This project aims to detect fraudulent credit card transactions using supervised machine learning techniques. With the rapid growth in credit card usage, detecting fraud effectively has become crucial to minimize financial losses. We leverage the power of decision trees and random forests to identify fraudulent activities based on transaction features.
# Dataset Description
- The dataset used for this project contains anonymized credit card transactions, labeled as either fraudulent or genuine. The dataset includes the following columns:

- Time: The time elapsed since the first transaction in the dataset.
- V1, V2, ..., V29: Principal component analysis (PCA) transformed features to protect sensitive data.
- Amount: Transaction amount.
- Class: The target variable, where 1 indicates a fraudulent transaction, and 0 indicates a genuine one.
# Project Structure
The project is organized into the following sections:

- Data Loading: Importing the dataset using pandas.
- Data Analysis & Visualization:
- Analysis of missing values.
- Calculation of the number of genuine and fraud transactions.
- Visualization of fraud vs. genuine transactions using bar plots.
- Additional visualizations for feature analysis and transaction patterns.
- Data Preprocessing:
- Normalization of the Amount column using StandardScaler.
- Splitting the dataset into training and testing sets (70:30 split).
# Model Building:
- Implementation of Decision Tree and Random Forest classifiers.
# Model Evaluation:
- Comparison of model predictions using accuracy, confusion matrix, and classification report.
- Performance comparison and determination of the better model.
# Additional Visualizations:
- Feature importance analysis using Random Forest.
- Visualization of confusion matrices.
# Project Requirements
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
# Model Evaluation
- After training and testing the models, we evaluated their performance based on:

- Accuracy Score: The proportion of correctly predicted instances.
- Confusion Matrix: A summary of prediction results on the classification problem.
- Classification Report: Includes precision, recall, F1-score, and support metrics.
# Decision Tree Results:

- Accuracy: 99.9142
- Precision, Recall, F1-Score: Detailed in the classification report.
# Random Forest Results:

- Accuracy: 99.885%  
- Precision, Recall, F1-Score: Detailed in the classification report.
# Conclusion
- decision Tree Model and Random Forest  model boths have similary accuracy terms of accuracy and precision.
- Feature importance analysis revealed that V17, V12, and V14 were among the most significant predictors for detecting fraud.
