# Forecasting of Smart City Traffic Patterns

## Project Overview

This project aims to predict traffic volume at various junctions using machine learning models. The project was undertaken as part of an internship with uniConverge Technologies Private Limited and Upskill Campus. Three different models were used for the predictions: XGBoost, Random Forest, and LSTM (Long Short-Term Memory) neural networks. The performance of these models was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared metrics.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
  - [XGBoost Model](#xgboost-model)
  - [Random Forest Model](#random-forest-model)
  - [LSTM Model](#lstm-model)
- [Evaluation Metrics](#evaluation-metrics)
- [Visualizations](#visualizations)


- [Acknowledgements](#acknowledgements)

## Dataset

The dataset used in this project contains traffic volume data at various junctions. The data includes timestamps, vehicle counts.

## Data Preprocessing

The data preprocessing steps include:
1. Parsing the `DateTime` column to extract date and time components.
2. Creating new features such as `DayOfWeek`, `Month`, and `Year`.
3. Determining if a given date is a holiday in India using the `holidays` library.
4. Adding lag features for previous day and previous hour vehicle counts.
5. Encoding categorical variables and scaling the features.

## Modeling

### XGBoost Model

The XGBoost model was trained using the following steps:
1. Preparing the data in DMatrix format.
2. Defining the model parameters.
3. Training the model with early stopping.

### Random Forest Model

The Random Forest model was trained using the following steps:
1. Initializing the Random Forest Regressor.
2. Training the model on the training dataset.

### LSTM Model

The LSTM model was trained using the following steps:
1. Scaling and reshaping the data for LSTM.
2. Defining the LSTM architecture.
3. Compiling and training the model.

## Evaluation Metrics

The performance of the models was evaluated using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-squared (R²)**
- **Root Mean Square Error (RMSE)**

## Visualizations


Plotly was used to create visualizations 
1. **Traffic Volume over time**
2. **Average Vehicles by Junction**
3. **Distribution of Vehicles by Holiday**
4. **Actual vs Predicted Values** for all models

## Acknowledgements

This project was completed as part of an internship with uniConverge Technologies Private Limited and Upskill Campus. Special thanks to the mentors and team members for their guidance and support.

---
