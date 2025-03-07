Human Activity Recognition using Smartphone Data
📌 Overview
This project uses machine learning models to classify human activities based on smartphone sensor data. The dataset contains accelerometer and gyroscope readings from multiple subjects performing different activities.

📂 Dataset
Source: [UCI Human Activity Recognition Dataset](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones/code)
Features: 561 extracted features from smartphone sensor signals
Target Labels: Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying
🛠️ Models & Performance
The following machine learning models were trained and evaluated:

Model	Accuracy (%)
Logistic Regression (LR)	96.06
Support Vector Machine (SVM)	96.50
Decision Tree (DT)	84.20
Random Forest (RF)	92.80
📉 Feature Reduction using PCA
Principal Component Analysis (PCA) was applied to reduce dimensions from 561 features to 2, achieving a 99.64% reduction.
Explained Variance Ratio: 0.6717
📌 Implementation Steps
Data Preprocessing (Scaling, Normalization)
Feature Selection using PCA
Model Training & Hyperparameter Tuning
Performance Evaluation
