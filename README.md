# SNP500 Stock Prediction
This repository contains the code and resources for a machine learning project that predicts good/bad stocks from the SNP500. The project is implemented in Python using Jupyter Notebook.

## Background
This project was completed as part of an honorary academic program in machine learning. The goal of the project was to gain experience in working with financial data and machine learning techniques, and to produce a proof-of-concept model for predicting good/bad stocks from the SNP500.

## Dataset
The dataset used in this project contains daily stock prices for the companies in the SNP500 index from January 2019 to December 2022. The dataset was obtained from Yahoo Finance and contains information on the open, high, low, and close prices, as well as the volume and adjusted close price for each stock.

## Steps
Data Collection and Preprocessing
The first step of the project was to collect and preprocess the data. This involved downloading the data from Yahoo Finance using the yfinance package, and cleaning the data by removing missing values, outliers, and other anomalies.

## Feature Engineering
The next step was to engineer features from the data that might be useful for predicting good/bad stocks. This involved calculating various technical indicators such as moving averages, relative strength index (RSI), and stochastic oscillator, as well as creating lagged variables to capture temporal dependencies in the data.

## Model Training and Evaluation
The final step was to train and evaluate several machine learning models on the engineered data. We used a variety of algorithms, including logistic regression, decision trees, random forests, and gradient boosting, and evaluated their performance using metrics such as accuracy, precision, recall, and F1 score.

## Conclusion
This project represents a first step into the field of machine learning for financial data. While the results are promising, there is still much room for improvement, and the project will be expanded and refined as the semester progresses. By continuing to experiment with different modeling techniques and feature engineering methods, we hope to create a more accurate and robust model for predicting good/bad stocks from the SNP500.
