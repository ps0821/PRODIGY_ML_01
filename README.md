# House Price Prediction using Linear Regression

This repository contains a linear regression model implementation to predict house prices based on their square footage, number of bedrooms, and number of bathrooms. The dataset used for this project is sourced from the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) competition on Kaggle.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
House prices vary based on several factors such as location, size, number of bedrooms, and number of bathrooms. This project aims to build a linear regression model to predict house prices using some of these features. Linear regression is a simple yet powerful tool for predictive modeling and is widely used in the field of data science.

## Dataset
The dataset used in this project is from the Kaggle competition "House Prices - Advanced Regression Techniques". The dataset contains various features of houses, but for this project, we will focus on the following:
- `GrLivArea`: Above grade (ground) living area square footage
- `BedroomAbvGr`: Number of bedrooms above basement level
- `FullBath`: Number of full bathrooms above basement level
- `SalePrice`: Sale price of the house (target variable)

You can download the dataset from [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib

You can install the required libraries using pip:

pip install pandas numpy scikit-learn matplotlib

<h1><b>Usage</b></h1>

##Clone the repository:

git clone https://github.com/your-username/house-price-prediction.git

##Navigate to the project directory:

cd house-price-prediction

##Download the dataset from Kaggle and place the train.csv file in the project directory.

##Run the house_price_prediction.py script to train the model and make predictions:

python house_price_prediction.py

<h1><b>Model</b></h1>

The linear regression model is implemented using the scikit-learn library. The key steps involved are:

##Data Preprocessing: Handling missing values and selecting relevant features.

##Feature Engineering: Extracting features (GrLivArea, BedroomAbvGr, FullBath) and target variable (SalePrice).

##Model Training: Training a linear regression model on the training dataset.

##Model Evaluation: Evaluating the model performance using metrics such as Mean Absolute Error (MAE) and R-squared.

<h1><b>Results</b></h1>

The performance of the linear regression model is evaluated using the Mean Absolute Error (MAE) and R-squared metrics. Detailed results and visualizations are provided in the results directory.

