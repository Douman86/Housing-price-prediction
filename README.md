Boston Housing Prices Prediction

This project aims to predict the median value of owner-occupied homes in the Boston area using various machine learning algorithms. The dataset used in this project is the Boston Housing dataset, which contains information about different housing factors in the Boston suburbs.

Features

The dataset contains the following features:

CRIM: per capita crime rate by town
ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS: proportion of non-retail business acres per town
CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
NOX: nitric oxides concentration (parts per 10 million)
RM: average number of rooms per dwelling
AGE: proportion of owner-occupied units built prior to 1940
DIS: weighted distances to five Boston employment centers
RAD: index of accessibility to radial highways
TAX: full-value property-tax rate per $10,000
PTRATIO: pupil-teacher ratio by town
LSTAT: percentage of lower status of the population
The target variable is:

MEDV: Median value of owner-occupied homes in $1000s
Workflow

The project workflow is as follows:

Import libraries and load the dataset
Perform exploratory data analysis (EDA) to understand the data
Visualize the features using histograms and scatter plots
Split the data into training and testing sets
Perform feature scaling
Train various machine learning models
Evaluate model performance using mean squared error (MSE) and R-squared
Perform hyperparameter tuning using GridSearchCV
Save the best models to disk
Load a saved model and make predictions on new data
Models Used

The following machine learning models are used in this project:

Linear Regression
Ridge Regression
Lasso Regression
ElasticNet
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Usage

To run the project, execute the Jupyter Notebook file boston_housing_prices_prediction.ipynb in a Jupyter environment. Make sure to install the required libraries mentioned in the requirements.txt file.

License

This project is licensed under the MIT License.
