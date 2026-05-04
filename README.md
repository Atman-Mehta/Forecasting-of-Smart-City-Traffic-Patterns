# Forecasting of Smart City Traffic Patterns

## Overview
Built an end-to-end ML system to predict traffic volume 
at city junctions, enabling proactive congestion management 
instead of reactive responses. Trained on 115,000+ real 
traffic records across multiple junctions.

## Results
- 15% reduction in traffic volume prediction error 
  after hyperparameter tuning
- XGBoost outperformed baseline on structured features
- LSTM captured sequential time dependencies effectively

## Technical Approach
- Engineered 12 temporal features including hour_of_day, 
  is_peak_hour, day_of_week, is_holiday, lag features
- Benchmarked XGBoost, Random Forest and LSTM pipelines
- Evaluated using MAE, RMSE and R² metrics

## Models Used
- XGBoost — best on tabular structured features
- Random Forest — robust baseline comparison  
- LSTM — captures sequential traffic dependencies

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, 
TensorFlow, Plotly, Flask
