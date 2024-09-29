# Calories Burn Prediction System
This system is designed to predict the number of calories burned during exercise sessions based on various factors such as gender, age,weight, exercise type, and weather conditions.

# Table of Contents
- Introduction
- Dataset
- Dependencies
- Usage
- Model Training
- Evaluation
- License

# Introduction

The Calories Burn Prediction System is developed to assist individuals in estimating the number of calories they might burn during different exercise routines. By utilizing machine learning techniques, the system predicts calorie burn based on inputs such as gender, age, weight, exercise type, and weather conditions.

# Dataset
The system employs a dataset consisting of various exercise sessions with corresponding calorie burn measurements. The dataset includes the following columns:

ID: Unique identifier for each exercise session

Gender: Gender of the participant (Male or Female)

Age: Age of the participant in years

Actual Weight: Weight of the participant in kilograms

Exercise: Type of exercise performed

Weather Conditions: Weather conditions during the exercise session

Calories Burn: Number of calories burned during the exercise session (target variable)

# Dependencies

The system requires the following dependencies:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- XGBoost
- Scikit-learn

# Usage
To use the Calories Burn Prediction System:

- Ensure all dependencies are installed.
- Download the dataset exercise_dataset.csv.
- Run the provided Python script to train the model and make predictions.
- Model Training

The system employs the Linear Regression and XGBoost Regressor  algorithms for regression to train the model. The training data is split into training and testing sets using a ratio of 80:20. The model is trained on features such as gender, age, weight,  exercise type, and weather conditions to predict calorie burn.

- Evaluation

The model's performance is evaluated using Mean Absolute Error (MAE). MAE measures the average absolute difference between the predicted and actual calorie burn values. Lower MAE indicates better predictive performance.
