# Afame-Technologies
Project 1
# HR Data Analysis Project
## Introduction
This project involves a comprehensive data cleansing process for an HR dataset. The goal is to prepare the data for effective analysis by removing irrelevant information, handling missing values, eliminating redundancies, and making other necessary adjustments. This process ensures the dataset is clean, consistent, and ready for further analysis or modeling.

## Data Cleansing Steps
### 1. Remove Unnecessary Columns
Identify and remove columns that are not useful for analysis.
### 2. Rename Columns
Give columns meaningful names to enhance readability and understanding.
### 3. Eliminate Redundant Entries
Remove duplicate rows to ensure unique entries.
### 4. Eliminate NaN Values
Address NaN values by either dropping or filling them with appropriate values.
### 5. Additional Changes
- Handle outliers
- Standardize/Normalize numerical columns

## Repository Structure
- **data/**
  - `hr_data.csv`: Original dataset
  - `cleaned_hr_data.csv`: Cleaned dataset

## Conclusion

By following these data cleansing steps, the HR dataset is now clean, consistent, and ready for detailed analysis. This preparation is essential for accurate and reliable insights, which can significantly impact HR decision-making processes.

Project 2
## Titanic Data Analysis Project
This project aims to predict whether a passenger on the Titanic survived or not using machine learning techniques. The dataset used for this project contains information about individual passengers, such as their age, gender, ticket class, fare, cabin, and whether or not they survived.

## Dataset
The dataset (titanic_dataset.csv) used for this project is available in this repository. It contains the following columns:
PassengerId: Unique identifier for each passenger
Survived: Whether the passenger survived (1) or not (0)
Pclass: Ticket class (1st, 2nd, or 3rd)
Name: Passenger's name
Sex: Passenger's gender
Age: Passenger's age
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Approach
Data Exploration: Understand the structure of the dataset, examine the features, and look for any missing values or outliers.
Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features if necessary.
Feature Engineering: Create new features or transform existing ones to better represent the data.
Model Selection: Choose appropriate machine learning algorithms for the problem. Common choices include logistic regression, decision trees, random forests, and gradient boosting machines.
Model Training: Split the dataset into training and testing sets, and train the chosen models on the training data.
Model Evaluation: Evaluate the performance of the models using appropriate metrics (e.g., accuracy, precision, recall, ROC AUC score) on the test set.

## Results
After experimenting with different models and feature engineering techniques, the best-performing model achieved an accuracy of 82.6% is Random Forest on the test set.
