# ML-Mid-Project
Salary Prediction using Machine Learning

This project focuses on predicting salaries based on various factors such as experience, age, education, and job role using machine learning algorithms.

Project Overview

The goal of this project is to:

Perform Exploratory Data Analysis (EDA)
Preprocess data for machine learning
Train multiple regression models
Compare model performance
Visualize results
Dataset Features

The dataset includes the following features:

Age – Age of the employee
Experience – Years of experience
Education – Education level (Bachelors, Masters, PhD)
Job Role – Position in the company
Salary – Target variable
 Exploratory Data Analysis (EDA)

The project includes:

Dataset info and structure
Statistical summary
Missing value analysis
Scatter plots:
Experience vs Salary
Age vs Salary
 Data Preprocessing
Categorical features encoded using Label Encoding
Features and target separated
Dataset split into training and testing sets (80/20)
Machine Learning Models

Two regression algorithms are implemented:

1. Linear Regression
Simple baseline model
Fast and interpretable
2. Random Forest Regressor
Ensemble model
Handles non-linear relationships better
Model Evaluation

Models are evaluated using:

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
R² Score
Visualization
Scatter plots for feature relationships
Line plots comparing:
Actual vs Predicted values
Linear Regression vs Random Forest predictions
Technologies Used
Python 
Pandas
NumPy
Matplotlib
Scikit-learn
 
 How to Run

Clone the repository:

git clone https://github.com/your-username/salary-prediction.git

Install dependencies:

pip install pandas numpy matplotlib scikit-learn

Run the notebook:

jupyter notebook ML_SalaryPredictionProject.ipynb

 Future Improvements
Use more advanced models (XGBoost, Gradient Boosting)
Hyperparameter tuning
Feature engineering
Deploy as a web app

Author
Namarta
