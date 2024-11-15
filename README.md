# Stock Price Prediction with Machine Learning Models 

This repository provides an implementation of various machine learning models for predicting stock prices. The project includes two datasets and multiple models, including K-Nearest Neighbors (KNN), Multilayer Perceptron Regressor (MLPR), Long Short-Term Memory (LSTM), Support Vector Regressor (SVR), Random Forest (RF), XGBoost, and an ensemble model that combines multiple algorithms.

## Project Structure 
 
- **data** : Contains CSV files with historical stock data for two companies: 
  - `TAINWALCHM.csv`: Stock data for the company TAINWALCHM.
 
  - `AGROPHOS.csv`: Stock data for the company AGROPHOS.
 
- **KNN+MLPR+LSTM+SVR** : Contains implementations of four machine learning models: 
  - **Models** : K-Nearest Neighbors (KNN), Multilayer Perceptron Regressor (MLPR), Long Short-Term Memory (LSTM), and Support Vector Regressor (SVR).
 
  - **Notebooks** : Two Jupyter notebooks, one for each dataset (TAINWALCHM and AGROPHOS).
 
- **rf_xgb_ensemble** : Contains implementations of: 
  - **Models** : Random Forest (RF), XGBoost, and an ensemble model that stacks Random Forest, XGBoost, and LSTM.
 
  - **Notebooks** : Two Jupyter notebooks, one for each dataset.
