# House Price Prediction using Linear Regression

## Project Overview

This project predicts house prices using Machine Learning and Linear Regression. The model uses different house-related features such as area, number of bedrooms, number of bathrooms, age of the house, and location score to estimate the house price.

The project demonstrates the basic workflow of a machine learning regression problem, including data loading, data exploration, feature selection, model training, prediction, evaluation, and visualization.

## Objectives

- To analyze house price data.
- To identify important features used for house price prediction.
- To build a Linear Regression model.
- To predict house prices based on input features.
- To evaluate the performance of the trained model using standard regression metrics.
- To compare models using different numbers of features.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset

The dataset contains information about houses and their corresponding prices.

## Features Used

Feature| Description
Area| Area/size of the house
Bedrooms| Number of bedrooms
Bathrooms| Number of bathrooms
Age| Age of the house
Location Score| Numerical score representing the location
Price| Target variable representing the house price

## Machine Learning Algorithm

Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict a continuous numerical value.

In this project, Linear Regression learns the relationship between the house features and the house price.

The model is trained using the selected input features and then used to predict prices for unseen test data.

## Project Workflow

1. Import the required Python libraries.
2. Load the house price dataset using Pandas.
3. Explore the dataset using:
   - "head()"
   - "info()"
   - "describe()"
   - Missing-value checking
4. Select the input features and target variable.
5. Split the dataset into training and testing data.
6. Train the Linear Regression model.
7. Predict house prices using the test data.
8. Evaluate the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score
9. Visualize actual and predicted prices.
10. Compare the model using five features and three features.

## Model Evaluation

The following metrics are used to evaluate the regression model:

- MAE: Measures the average absolute difference between actual and predicted prices.
- MSE: Measures the average squared difference between actual and predicted prices.
- RMSE: Represents the square root of MSE and indicates the typical prediction error.
- R² Score: Indicates how well the model explains the variation in house prices.

## Feature Comparison

Two Linear Regression models are compared:

Model 1 – Five Features

The first model uses:

- Area
- Bedrooms
- Bathrooms
- Age
- Location Score

Model 2 – Three Features

The second model uses:

- Area
- Bedrooms
- Location Score

The R² scores of both models are compared to understand the effect of using different feature sets.

## Visualization

The project includes a scatter plot comparing:

- Actual House Prices
- Predicted House Prices

A reference line is also plotted to observe how closely the predicted values match the actual values.

## Project Structure

House-Price-Prediction/
│
├── houseprice.ipynb
├── house_prices.csv
└── README.md

## How to Run the Project

1. Clone or download this repository.
2. Make sure Python is installed.
3. Install the required libraries:

pip install pandas numpy scikit-learn matplotlib jupyter

4. Open the Jupyter Notebook:

jupyter notebook houseprice.ipynb

5. Make sure "house_prices.csv" is placed in the same folder as the notebook.
6. Run the notebook cells in order.

## Results

The trained Linear Regression model generates house price predictions based on the selected features. The model performance is evaluated using MAE, MSE, RMSE, and R² score.

The project also compares the performance of models trained with five features and three features.

## Conclusion
This project demonstrates how Linear Regression can be used for house price prediction. It covers the complete basic machine learning workflow, from data preprocessing and feature selection to model training, prediction, evaluation, and visualization.

## Future Improvements
The project can be further improved by:

- Using a larger and more diverse dataset.
- Applying additional machine learning algorithms.
- Performing feature engineering.
- Applying cross-validation.
- Hyperparameter tuning where applicable.
- Developing a simple web application for real-time house price prediction.

## Author
Hemadharshini V.
B.Tech – Information Technology
