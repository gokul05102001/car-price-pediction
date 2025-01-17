# car-price-pediction
This project aims to predict car prices in the US market using multiple regression models, helping a Chinese automobile company entering the US market to understand the factors influencing car prices. This model will aid in strategizing car designs, pricing, and business approaches to compete effectively in the US automotive market.

### Business Objective
The goal is to model car prices using independent variables from a dataset of different types of cars in the American market. The project addresses the following key questions:

* Which variables are significant in predicting car prices?
* How well do these variables explain car prices?
## 1. Loading and Preprocessing (5 marks)
Load the dataset into a pandas DataFrame.
Handle missing values (impute or drop).
Handle categorical variables (use encoding like one-hot or label encoding).
Scale/normalize numerical features if necessary.
Split the data into training and testing sets (e.g., 80-20 split).
## 2. Model Implementation (10 marks)
Implement the following regression algorithms:

Linear Regression: A baseline model for comparison.
Decision Tree Regressor: Captures non-linear relationships.
Random Forest Regressor: An ensemble method to reduce overfitting.
Gradient Boosting Regressor: Boosted ensemble method for better accuracy.
Support Vector Regressor (SVR): Uses kernels to handle non-linearity.
Steps:

Train each model on the training set.
Predict car prices on the test set.
## 3. Model Evaluation (5 marks)
Evaluate each model using:

R-squared (R²): Measures how well the model explains variance.
Mean Squared Error (MSE): Penalizes large errors.
Mean Absolute Error (MAE): Reflects absolute deviation.
Summarize the performance of each model in a table.

Identify the best-performing model and justify your choice.

## 4. Feature Importance Analysis (2 marks)
For models like Random Forest and Gradient Boosting, extract feature importance.
For Linear Regression, look at coefficients.
Analyze which features have the most significant impact on car prices.
