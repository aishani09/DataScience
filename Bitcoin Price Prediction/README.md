# Bitcoin Price Prediction

## Overview
This project focuses on predicting Bitcoin prices using machine learning and deep learning techniques. The model analyzes historical price data and attempts to forecast future prices based on various technical indicators and time-series analysis.

## Dataset
The dataset used for this project includes:

- Historical Bitcoin prices
- Open, High, Low, Close (OHLC) values
- Volume traded
- Time-series data for trend analysis


## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib/Seaborn (for visualization)
- TensorFlow/Keras (for deep learning models)


## Features

- Data preprocessing and cleaning
- Feature engineering
- Exploratory Data Analysis (EDA)
- Feature selection using Partial Least Squares Structural Equation Modeling (PLS-SEM)
- Model selection (Linear Regression, LSTM, Random Forest, ANN, etc.)
- Model evaluation using RMSE, MAE, and R-squared metrics
- Visualization of predictions vs actual prices


## Feature Selection Using PLS-SEM
To improve model performance and reduce dimensionality, we apply Partial Least Squares Structural Equation Modeling (PLS-SEM) to extract the most relevant features before feeding the data into our deep learning model.


## ANN Model for Bitcoin Price Prediction
We utilize an Artificial Neural Network (ANN) to predict Bitcoin prices. The model consists of multiple dense layers with LeakyReLU activation, batch normalization, and dropout layers to improve generalization and prevent overfitting.


## Results
The project provides insights into Bitcoin price trends and predictions using machine learning models. It evaluates model performance and suggests potential improvements.
