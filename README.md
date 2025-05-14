# Bitcoin Price Prediction Using Machine Learning

This project implements various machine learning models to predict Bitcoin prices using historical price data and sentiment analysis from Reddit posts.

## Overview

- **Models Used**: Random Forest, LSTM (using PyTorch), and regression models.
- **Data**: Over 3 million rows of historical Bitcoin price data.
- **Sentiment Analysis**: Integrated Reddit sentiment data using [TextBlob](https://textblob.readthedocs.io/) for enhanced feature extraction.
- **Performance**: Achieved a final Mean Absolute Percentage Error (MAPE) of **2.6%**.

## Features

- Time-series forecasting with LSTM neural networks.
- Ensemble learning with Random Forest.
- NLP-driven sentiment feature engineering.
- Data preprocessing and scaling.
- Model training, evaluation, and comparison.

## Technologies

- Python
- PyTorch
- scikit-learn
- TextBlob
- Pandas / NumPy
