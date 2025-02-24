
# Machine Learning - Assignment 1

## Overview

In this first assignment, we worked with the Boston housing dataset to see various machine learning techniques. The goal was to understand how to preprocess data, apply different regression models, and visualize the results. We used NumPy, Pandas, Matplotlib, and Scikit-learn to accomplish this.

## Key Steps

1. **Data Loading**: We started by loading the Boston housing dataset using the `fetch_openml` function from Scikit-learn. This dataset contains information about various features of houses in Boston and their corresponding prices.

2. **Data Preprocessing**: 
   - We converted the data into a Pandas DataFrame for easier manipulation.
   - We set display options to ensure that we could see all relevant columns when printing the DataFrame.

3. **Data Splitting**: 
   - We split the dataset into training and testing sets using an 80-20 split. This is crucial for evaluating the performance of our models on unseen data.

4. **Data Standardization**: 
   - We standardized the features using `StandardScaler` to ensure that all features contribute equally to the model training.

5. **Model Training**: 
   - We applied three different regression models: Lasso, Ridge, and ElasticNet, using cross-validation to find the best hyperparameters for each model.

6. **Predictions and Evaluation**: 
   - After training the models, we made predictions on the test set and calculated the Mean Squared Error (MSE) for each model to evaluate their performance.

7. **Visualization**: 
   - We created plots to visualize the Mean Squared Error for each model across different hyperparameters. This helped us understand how each model performed and identify the optimal parameters.
