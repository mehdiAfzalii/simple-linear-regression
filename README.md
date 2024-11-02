# Salary Prediction Using Simple Linear Regression

This project uses simple linear regression to predict employees' salaries based on their years of experience. The dataset (`Salary_Data.csv`) includes information on the years of experience and corresponding salaries of various employees. The model is trained on part of the data, and predictions are made on a separate test set.

## Project Overview

1. **Data Loading**: The dataset is loaded from `Salary_Data.csv`.
2. **Data Splitting**: The data is split into training and testing sets (80% training, 20% testing).
3. **Model Training**: A linear regression model is trained on the training data.
4. **Prediction and Visualization**: The model predicts salaries based on the test data, and results are visualized for both the training and test sets.

## Requirements

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

You can install the required packages using:

```bash
pip install numpy pandas matplotlib scikit-learn


Usage
Place the Salary_Data.csv file in the same directory as the script.
Run the script to train the model and visualize the results.
Dataset
The dataset should contain two columns:

Years of Experience: Numeric values representing years of experience.
Salary: Numeric values representing salary in dollars.
Visualizations
Two plots are generated:

Training Set Plot: Shows actual salaries and the regression line for the training data.
Test Set Plot: Shows actual salaries and the regression line for the test data.