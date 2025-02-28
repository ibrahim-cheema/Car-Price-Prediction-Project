Car Price Prediction

Overview

This project implements multiple machine learning models to predict car selling prices based on various features such as fuel type, seller type, and transmission type. The dataset used for training and testing is car_data.csv.

Features Used

The following features are used as input for the models:

Fuel Type (Categorical, Encoded)

Seller Type (Categorical, Encoded)

Transmission (Categorical, Encoded)

Other numerical attributes

Machine Learning Models Used

Linear Regression

Lasso Regression

Random Forest Regressor

Installation

Ensure you have Python and the required libraries installed before running the project.

Required Libraries

Install the required libraries using:

pip install pandas matplotlib seaborn scikit-learn

Dataset

The dataset (car_data.csv) should be placed in the root directory of the project. It contains various attributes of cars along with their selling price.

Steps Performed

Load the dataset and inspect its structure.

Handle missing values (if any).

Encode categorical variables using LabelEncoder.

Split the dataset into training and testing sets.

Train and evaluate:

Linear Regression

Lasso Regression

Random Forest Regressor

Compute R-squared error scores for performance evaluation.

Visualize predictions against actual prices using scatter plots.

Usage

Run the script using:

python car_price_prediction.py

Make sure the dataset file is present in the directory.

Results

The models predict the selling price of cars.

Scatter plots are generated to compare actual vs. predicted prices for both training and testing data.

R-squared error is calculated to measure performance.
