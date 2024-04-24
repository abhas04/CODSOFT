# SALES PREDICTION 

This project aims to predict sales based on advertising spending using the Linear Regression machine learning algorithm. The dataset used contains information about advertising spending on TV, Radio, and Newspaper, along with corresponding sales figures.

## Overview

The provided code performs the following tasks:

1. **Data Loading and Exploration**: 
    - Loads the advertising dataset (`advertising.csv`) using Pandas.
    - Displays basic information about the dataset including the last few rows, descriptive statistics, and checking for missing values.

2. **Data Preprocessing**:
    - Splits the dataset into features (`X`: TV, Radio, Newspaper) and target variable (`Y`: Sales).
    - Splits the data into training and testing sets using a 80-20 split ratio.

3. **Model Training**:
    - Trains a Linear Regression model using the training data.

4. **Model Evaluation**:
    - Predicts sales using the trained model on the testing data.
    - Calculates the Mean Squared Error (MSE) to evaluate model performance.

5. **Visualizations**:
    - Scatter plot of Actual vs Predicted Sales.
    - Bar plot of Feature Importance based on Coefficients.

6. **Making Predictions with New Data**:
    - Provides an example of making predictions using new data in DataFrame format.
    - The predicted sales values for the new data are displayed.

## Results

- **Mean Squared Error (MSE)**: The MSE for the Linear Regression model is approximately 2.91.
- **Feature Importance**:
    - The coefficient values indicate the importance of each feature in predicting sales.
    - Features are ranked based on their absolute coefficient values.
    - The most important feature is Radio, followed by TV and Newspaper.
- **Predicted Sales**: For the given example of new data, the predicted sales values are approximately 12.36 and 18.86.

    The "Predicted Sales" output represents the predicted sales values for new data points provided to the trained Linear Regression model. In the provided example, the model is given new data containing information about advertising spending on TV, Radio, and Newspaper for two scenarios.

    The output `[12.35742661, 18.86117378]` indicates the predicted sales values for these two scenarios:

    1. For the first scenario, the model predicts sales to be approximately 12.36 units.
    2. For the second scenario, the model predicts sales to be approximately 18.86 units.

    These predicted sales values are based on the patterns learned by the Linear Regression model during training, where it analyzed the relationship between advertising spending on different mediums and the resulting sales figures. The model then applies this learned relationship to make predictions on new, unseen data.


## Usage

To run the code:
1. Ensure you have Python and the required libraries installed.
2. Download the `advertising.csv` dataset.
3. Copy and paste the provided code into a Python script or Jupyter Notebook.
4. Run the script or notebook.

## Dependencies

- Pandas
- NumPy
- Matplotlib
- scikit-learn


