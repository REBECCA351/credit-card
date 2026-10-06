💳 Credit Card Default Prediction Using Machine Learning
📌 Project Overview
This project focuses on predicting whether a credit card customer is likely to default on their payment using Machine Learning techniques.
The project uses customer-related information such as credit limit, demographic details, payment history, and bill/payment amounts to build classification models.
The main goal is to perform data preprocessing, exploratory data analysis (EDA), feature selection, model training, and model evaluation to identify the most suitable Machine Learning algorithm for credit card default prediction.
🎯 Objectives
To understand and preprocess the credit card dataset.
To perform Exploratory Data Analysis (EDA).
To handle categorical and numerical features.
To identify and handle outliers and skewed data.
To perform feature selection.
To scale the required features.
To build multiple Machine Learning classification models.
To compare model performance using evaluation metrics.
To identify the best-performing model.
📊 Dataset
The dataset contains customer information related to credit card usage and payment behaviour.
Important Features
ID – Customer identification number
LIMIT_BAL – Amount of given credit
SEX – Gender
EDUCATION – Education level
MARRIAGE – Marital status
AGE – Customer age
PAY_0, PAY_2, ... – Repayment status
BILL_AMT1, BILL_AMT2, ... – Bill statement amounts
PAY_AMT1, PAY_AMT2, ... – Previous payment amounts
Target Variable – Credit card payment default status
🔄 Project Workflow
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis (EDA)
   ↓
Encoding
   ↓
Outlier Analysis
   ↓
Skewness Analysis
   ↓
Feature Selection
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Machine Learning Models
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Best Model Selection
🔍 Exploratory Data Analysis
The following steps were performed during EDA:
df.info()
df.describe()
df.shape
df.columns
Missing value analysis
Duplicate value analysis
Correlation analysis
Heatmap visualization
Box plot analysis
Outlier detection
Skewness analysis
These steps help to understand the structure, distribution, and relationships within the dataset.
🛠️ Data Preprocessing
The dataset was prepared for Machine Learning using the following techniques:
Handling missing values
Checking duplicate records
Encoding categorical features
Identifying outliers
Handling skewed features
Feature selection using SelectKBest
Feature scaling using StandardScaler
🤖 Machine Learning Algorithms
The following classification algorithms were implemented:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
AdaBoost Classifier
Gradient Boosting Classifier
The models were trained using the training dataset and evaluated using the testing dataset.
📈 Model Evaluation
The models are compared using the following classification metrics:
Metric
Description
Accuracy
Measures the overall percentage of correct predictions
Precision
Measures how many predicted positive cases were actually positive
Recall
Measures how many actual positive cases were correctly identified
F1-Score
Provides a balance between precision and recall
A model comparison table is created to identify the best-performing algorithm.
💻 Technologies Used
Python
Jupyter Notebook
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Results
Multiple Machine Learning classification algorithms were implemented and compared using Accuracy, Precision, Recall, and F1-Score.
The model with the best overall evaluation performance can be selected as the final model for credit card default prediction.
🎓 Conclusion
This project demonstrates how Machine Learning can be applied to credit card customer data to predict payment default behaviour.
The project covers the complete Machine Learning workflow, starting from data preprocessing and EDA to feature selection, scaling, model building, and performance evaluation.
