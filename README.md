## Machine Learning with PySpark - Loan Prediction

# Objective of the Project
This is a typical supervised classification task, where the objective is to predict whether a loan will be approved or not.

# Project Information
The aim of this project is to demonstrate the use of PySpark and Machine Learning to predict loan approvals. The project will include the following stages:
1. Data Collection: Collecting data related to loan approvals, including features such as income, credit score, loan amount, and loan status
2. Data Preparation: Cleaning and preprocessing the data to make it ready for use with Machine Learning algorithms.
3. Feature Engineering: Identifying and transforming key features to improve model accuracy.
4. Model Training: Using PySpark to train a Machine Learning model on the processed data.
5. Model Evaluation: Testing the model on a validation set to measure its accuracy and fine-tuning it if necessary.
6. Loan Prediction: Using the trained model to predict whether a loan will be approved based on specific input features.
This project requires knowledge of PySpark, Machine Learning, and Python. The result will be a model that can accurately predict loan approvals, helping financial institutions or individuals make better loan decisions. The project could be further enhanced by experimenting with various algorithms and improving model accuracy.


# Dataset Information
Dream Housing Finance, a company specializing in home loans, operates in urban, semi-urban, and rural areas. Customers first apply for a home loan, after which the company assesses their eligibility. They want to automate the loan eligibility process in real-time, based on the information provided by customers in the online application form. This includes details such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and more. The goal is to classify and identify customer segments eligible for loans, allowing the company to focus on these specific groups.

Download link: https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

# Libraries
1. pyspark
# Algorithms
1. Logistic Regression
2. Random Forest

# Result
We split the dataset for training set 80% and testing set 20%
1. Logistic Regression Model got AUC: 78.20%
2. Random Forest got AUC: 82.00 %

# What's Next?
1. Try to predict the loan with advanced machine learning algorithms.
2. Try to use different type of feature extraction process.


