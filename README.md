# CSC700

Customer Churn Prediction

Team Members & Skills

Rashed Adel – Data Analysis, Machine Learning, Visualization
Yousef Nasser – Data Preprocessing, Model Tuning, Report Writing
Jaber Al Kindi – Feature Engineering, Evaluation Metrics, Documentation

Project Overview

In this project, we developed a machine learning model to predict customer churn for a bank. The objective is to identify customers who are likely to leave the bank, enabling proactive customer retention strategies.

Process Summary

Exploratory Data Analysis (EDA): Conducted detailed EDA to understand the dataset and detect patterns, correlations, and anomalies.
Data Preprocessing: Cleaned and prepared data by handling missing values, encoding categorical features, and scaling numerical values.
Model Training & Testing: Multiple machine learning algorithms were tested. After evaluation, the best-performing model was selected.
Hyperparameter Tuning: Fine-tuned model parameters to enhance performance.
Model Evaluation: The final model was evaluated on unseen test data using accuracy, precision, F1 score, and ROC-AUC.
Best Model Performance

Model: LGBMClassifier
Hyperparameters:
Learning Rate: 0.05
Max Depth: 5
Estimators: 100
Performance Metrics:
Accuracy: 0.8670
Precision: 0.7571
F1 Score: 0.5844
ROC-AUC Score: 0.8741
The model showed strong performance in distinguishing between churn and non-churn customers. While results are promising, further improvement may be possible by experimenting with ensemble methods or additional feature engineering.

Future Work

Try ensemble models (e.g., stacking or blending)
Explore advanced feature selection techniques
Deploy the model for real-time predictions
