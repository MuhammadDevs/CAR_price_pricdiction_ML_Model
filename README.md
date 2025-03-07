# Car Price Prediction using Linear Regression

This project aims to predict car prices using a linear regression model. The dataset used contains information about various cars, including their features such as year, kilometers driven, fuel type, seller type, transmission type, and more. The goal is to build a model that can accurately predict the selling price of a car based on these features.


## Project Overview
The project involves the following steps:
- Loading and preprocessing the dataset.
- Encoding categorical variables using one-hot encoding.
- Splitting the data into training and testing sets.
- Training a linear regression model.
- Evaluating the model using metrics like R² score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
- Visualizing the results using scatter plots and residual plots.
- Testing the model with new data.

## Dataset
The dataset used in this project is `car data.csv`. It contains the following columns:
- `Car_Name`: Name of the car.
- `Year`: Manufacturing year of the car.
- `Selling_Price`: Selling price of the car (target variable).
- `Present_Price`: Current showroom price of the car.
- `Kms_Driven`: Kilometers driven by the car.
- `Fuel_Type`: Type of fuel used (Petrol, Diesel, CNG).
- `Seller_Type`: Type of seller (Dealer, Individual).
- `Transmission`: Transmission type (Manual, Automatic).
- `Owner`: Number of previous owners.

## Requirements
To run this project, you need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using `pip`:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
