# Task-6-House-Price-Prediction

##  Objective
The objective of this project is to predict house prices based on property features such as area, bedrooms, bathrooms, parking, and location using Machine Learning regression models.

This helps in estimating property values and understanding real estate trends.


##  Dataset
The dataset is obtained from Kaggle House Price Prediction Dataset.

It contains the following information:

- Area (Square Footage)
- Number of Bedrooms
- Number of Bathrooms
- Number of Stories
- Parking Availability
- Location Information
- Furnishing Status
- House Price (Target Variable)


##  Features Used

The following features are used as input variables:

- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Main Road Access
- Guest Room Availability
- Basement Availability
- Furnishing Status


##  Target Variable

The target variable is:

- Price → House price to be predicted

This is a continuous numerical value, so this is a Regression problem.


## Machine Learning Models Used

The following regression models were implemented:

- Linear Regression
- Gradient Boosting Regressor

These models learn patterns from historical data and predict house prices.


##  Project Workflow

The following steps were performed:

1. Import required libraries (pandas, numpy, sklearn, matplotlib)
2. Load dataset using pandas
3. Explore and understand dataset
4. Perform data preprocessing
   - Handle missing values
   - Convert categorical data using One-Hot Encoding
5. Define features (X) and target (y)
6. Split dataset into training and testing sets (80% training, 20% testing)
7. Apply feature scaling using StandardScaler
8. Train Linear Regression model
9. Train Gradient Boosting Regression model
10. Predict house prices using test data
11. Evaluate model performance using:
    - Mean Absolute Error (MAE)
    - Root Mean Squared Error (RMSE)
12. Visualize actual vs predicted prices using scatter plot


##  Evaluation Metrics

Two evaluation metrics were used:

### Mean Absolute Error (MAE)
Measures average prediction error.

Formula:

MAE = (1/n) × Σ |Actual − Predicted|


### Root Mean Squared Error (RMSE)
Measures prediction error with higher penalty for large errors.

Formula:

RMSE = √[(1/n) × Σ (Actual − Predicted)²]


##  Results

The models successfully predicted house prices.

Gradient Boosting Regressor provided better accuracy compared to Linear Regression.

Lower MAE and RMSE indicate better model performance.


##  Visualization

A scatter plot was used to compare:

- Actual Prices
- Predicted Prices

This helps visually evaluate model accuracy.


## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn



