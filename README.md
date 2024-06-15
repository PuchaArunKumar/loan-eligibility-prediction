# loan-eligibility-prediction
ML Hackathon conducted by capabl
#Overview
This repository contains the solution for the loan eligibility prediction problem provided by Dream Housing Finance company. The goal is to automate the loan eligibility process based on customer details provided in the online application form.

#Problem Statement
Dream Housing Finance company wants to automate the loan eligibility process (real-time) based on customer details such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, etc. The objective is to identify the customer segments eligible for loan amounts to target these customers specifically.


#Approach
#1. Data Loading and Preprocessing
Loaded the dataset and performed basic data inspection.
Handled missing values using appropriate imputation techniques.
Detected and treated outliers.
#2. Exploratory Data Analysis (EDA)
Conducted univariate analysis on categorical and numerical variables.
Performed bivariate analysis to understand relationships between features and the target variable.
Generated a correlation heatmap to study the correlations between numerical variables.
#3. Feature Engineering
Applied Label Encoding to convert categorical variables into numerical format.
Standardized numerical features for better model performance.
#4. Model Building
Split the data into training and testing sets.
Trained initial models using algorithms like Logistic Regression, Decision Tree, and Random Forest.
Evaluated model performance using accuracy, confusion matrix, and classification report.
#5. Model Tuning
Performed hyperparameter tuning using GridSearchCV to find the best model parameters.
Trained the final model with the best parameters and evaluated its performance.

#SResults
Achieved an accuracy of 78% on the test data using the final model.
Detailed performance metrics are available in the classification report and confusion matrix.
