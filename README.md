# Commodity Price Prediction in Central Java Using LSTM

## Description
This repository contains the implementation of an undergraduate thesis project entitled **"Commodity Price Prediction in Central Java Using Long Short-Term Memory (LSTM)"**. The study aims to predict daily food commodity prices in Central Java, Indonesia, using historical time series data.

## Dataset
The dataset used in this study consists of daily food commodity prices from **2020 to 2025**, obtained from the **National Strategic Food Price Information System (PIHPS)**.

Source:
https://hargapangan.id

The dataset is publicly accessible and is included in this repository for experimental transparency. The official data source remains PIHPS.

## Commodities
The commodities analyzed in this study include:
- Rice
- Chicken Meat
- Beef
- Eggs
- Shallots
- Red Chili
- Cayenne Pepper
- Cooking Oil
- Sugar

## Methodology
This research applies the **Long Short-Term Memory (LSTM)** method for time series forecasting. Two experimental scenarios are implemented:
- **Univariate LSTM**, using historical prices of a single commodity
- **Multivariate LSTM**, using multiple commodity price series as input features

## Data Preprocessing
The preprocessing stages include:
- Data integration across multiple years
- Handling missing values
- Min–Max normalization
- Sliding window transformation
- Chronological data splitting for training, validation, and testing

## Evaluation
Model performance is evaluated using **Mean Absolute Percentage Error (MAPE)** to measure prediction accuracy.
