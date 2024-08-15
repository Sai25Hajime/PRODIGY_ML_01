# PRODIGY_ML_01
I have implemented a linear regression model for our dataset called house price prediction according to Task-01: "Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms."
The goal is to find the best-fit line (regression line) that can predict the dependent variable based on the independent variables.

Here is the dataset used: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

# Steps for Using the Dataset
1) Download all the four files from the website
2) Upload them to your drive in a folder called Datasets to make things easier.
3) Then open Google Collab
4) Add a Code cell above the given code in the ipynb file to mount your Google drive.

# Code Execution:
The code is inside the House_Price_Prediction.ipynb file. Do the above steps and execute the code.

# Knowledge Gained
1. Efficient Data Loading and Usage:
Single Dataset Focus: Learned the importance of focusing on the correct dataset (train.csv) to ensure that the features and target variables used for training and evaluation are accurate.
Handling Multiple Data Sources: Gained insight into the practical implications of loading multiple datasets and the need to correctly use the intended dataset for analysis.

2. Feature Engineering:
Feature Selection: Applied skills in selecting relevant features (LotArea, BsmtFullBath, BsmtHalfBath, FullBath, HalfBath, BedroomAbvGr, TotRmsAbvGrd) that are predictive of house prices.
Data Preparation: Understood the importance of preparing and preprocessing data to be used effectively in a machine learning model.

3. Linear Regression Implementation:
Model Training: Implemented a linear regression model using scikit-learn, learning how to fit the model to the training data and make predictions.
Performance Metrics: Evaluated the model’s performance using Mean Squared Error (MSE) and R-squared metrics to understand prediction accuracy and model fit.

4. Data Visualization and Interpretation:
Scatter Plot Visualization: Developed skills in creating scatter plots to visualize the relationship between actual and predicted house prices.
Perfect Prediction Line: Learned to include a reference line in the plot to indicate the ideal prediction scenario, enhancing the interpretation of model performance.

5. Model Evaluation and Improvement:
Error Analysis: Gained experience in analyzing model performance and understanding the implications of evaluation metrics on model quality.
Visualization Insights: Used visualizations to gain insights into how well the model is predicting and identify potential areas for improvement.
This task provided hands-on experience with key machine learning concepts, including data handling, feature selection, model training, evaluation, and visualization, crucial for developing and assessing predictive models.
