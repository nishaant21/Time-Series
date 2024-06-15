# Time Series With LSTM: Air Quality Prediction Using LSTM

# Overview: This project aims to predict air quality, specifically the PM2.5 index, using a Long Short-Term Memory (LSTM) neural network. The dataset used contains historical PM2.5 measurements from various timestamps. The model is trained to understand patterns and trends in the data to make future predictions.

Goal: The goal of this analysis is to understand the patterns influencing air quality over time. By exploring various features such as timestamps and PM2.5 values, the aim is to build a predictive model to identify key drivers of air quality changes. The analysis seeks to uncover insights that can help in improving air quality management strategies.

## Introduction
Air quality prediction is crucial for environmental monitoring and public health. This project aims to predict the PM2.5 index, which is a common measure of air pollution, using machine learning techniques. Accurate predictions allow authorities to take proactive measures to improve air quality.

## Dataset
The dataset used in this project is air-quality-india.csv, which includes the following columns:

Timestamp: The date and time of the measurement.
PM2.5: The PM2.5 index value.

## Exploratory Data Analysis (EDA)
EDA is performed to understand the dataset better and to uncover patterns, anomalies, and relationships between variables. Various visualizations are used to summarize the main characteristics of the data.

## Feature Engineering
### Timestamp Conversion
Convert the Timestamp column to datetime format.
Extract date components (Year, Month, Day, Hour) from the 'Timestamp'.

### Data Preparation for Modeling
Scale the data using MinMaxScaler.
Split the data into training and testing sets.
Create sequences of data for the LSTM model.

## Machine Learning Models
### LSTM
The LSTM model is built using Keras and trained on the prepared data. The steps involved are:

1.Model Building
Build an LSTM model using Keras.
The model includes LSTM layers and Dense layers.

2.Model Training
Train the model on the training data with specified epochs and batch size.

3.Model Evaluation
Make predictions on the test data.
Evaluate the model using Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Result and Evaluation
The models are evaluated using metrics such as MSE, RMSE and MAE.

## Conclusion
This project demonstrates how to use an LSTM neural network to predict air quality based on historical PM2.5 data. The model's performance is evaluated using MSE, MAE, and RMSE metrics. The visualizations help in understanding the patterns in the data and the model's predictions.
