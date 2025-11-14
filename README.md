## Bitcoin Price Prediction Using LSTM

- This project focuses on predicting Bitcoin (BTC-USD) closing prices using a Long Short-Term Memory (LSTM) deep learning model.
- The dataset contains historical Bitcoin price details such as Date, Open, High, Low, Close, Adj Close, and Volume from 2014 to 2022.
- The project includes Exploratory Data Analysis (EDA), visualizations, model training, prediction, and evaluation.

## Dataset

### Dataset Used: BTC-USD
### Columns:

- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume
- Time Period: 2014 – 2022

## Table of Contents

- Importing Libraries

- Loading Dataset (BTC-USD)

- Exploratory Data Analysis (EDA)

- Analysis of Year 2015

- Analysis of Year 2016

- Analysis of Year 2017

- Analysis of Year 2018

- Analysis of Year 2019

- Analysis of Year 2020

- Analysis of Year 2021

- Overall Analysis (2014–2022)

### Visualization

- Building the LSTM Model

- Prediction

- Evaluation

## Exploratory Data Analysis (EDA)

The EDA section provides:
✔ Year-wise BTC price movement
✔ Volume trends
✔ Volatility patterns
✔ Key price jumps and corrections
✔ Trend comparison across years

The overall trend from 2014–2022 highlights major bull runs and corrections.

## Visualizations

- This project includes various visualizations such as:

- Year-wise closing price plots

- Bitcoin price trend over the entire period

- Volume comparison

- Actual vs Predicted price visualization

- Moving averages (optional)

## LSTM Model

- The LSTM model is built using:

- MinMaxScaler for normalization

- Sliding window technique for sequence preparation

- LSTM layers

- Dense output layer

- Adam optimizer and MSE loss

- The model learns sequential patterns in Bitcoin’s highly volatile price data.

## Prediction

- Once trained, the model predicts the Bitcoin closing price for the test period.
- Predicted vs Actual values are plotted to visualize model performance.
