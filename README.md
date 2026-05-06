Customer Purchase Prediction

Hi, this is my first machine learning project where I built a classification model to predict whether a customer is likely to purchase a product or not based on customer information.

In this project, I worked with a raw dataset containing customer details such as age, salary, city, and purchase status. The dataset had missing values and categorical data, so before building the model, I performed data exploration and preprocessing.

Problem Statement

To predict whether a customer will purchase a product based on factors like age, salary, and city.

Dataset Features

Input Features

- Age
- Salary
- City

Target Variable

- Purchased

What I Did in This Project

1. Data Loading

Loaded the dataset using Pandas in Jupyter Notebook.

2. Exploratory Data Analysis

To understand the dataset, I checked:

- first few rows of data
- missing values
- dataset structure

3. Data Preprocessing

I performed the following preprocessing steps:

- Removed duplicate records
- Handled missing values using mean imputation
- Converted categorical columns into numerical format using Label Encoding
- Applied feature scaling using StandardScaler

4. Feature Selection

Selected Age, Salary, and City as input features and Purchased as target variable.

5. Model Building

Used Logistic Regression to train the classification model.

6. Model Evaluation

Split the dataset into training and testing data using 70:30 ratio.

The model achieved an accuracy of 83.33% on test data.

Project Workflow

Raw Dataset → EDA → Data Preprocessing → Feature Selection → Feature Scaling → Train-Test Split → Model Training → Prediction → Evaluation

What I Learned

Through this project, I gained practical understanding of:

- Exploratory Data Analysis
- Handling missing values
- Label Encoding
- Feature Scaling
- Train-Test Split
- Logistic Regression
- Model Evaluation

This project helped me build confidence in implementing a complete machine learning workflow from scratch.

Author

Mamidi Sai Sujith
Aspiring Data Analyst | Learning Machine Learning step by step