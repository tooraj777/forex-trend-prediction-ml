# Forex Trend Prediction Using Machine Learning

**Machine Learning | Financial Time Series | Python | XGBoost | KNN**

## Overview

An experimental machine learning project focused on analyzing historical Forex market data and classifying potential price trends.

The project uses historical **USD/CHF four-hour (H4)** market data, technical indicators, and supervised machine learning algorithms to investigate patterns in financial time series.

## Features

- Historical Forex data preprocessing and cleaning
- Technical indicator-based feature engineering
- Trend classification into upward, downward, and neutral categories
- K-Nearest Neighbors (KNN) classification
- XGBoost-based classification experiments
- Model accuracy evaluation and feature importance analysis
- Experiments with chronological train/test splitting

## Technical Indicators

- Relative Strength Index (RSI)
- Average True Range (ATR)
- Moving averages: MA40, MA80, MA160

## Technology Stack

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Financial Time-Series Analysis

## Machine Learning Workflow

1. Load historical USD/CHF H4 data.
2. Clean and preprocess the dataset.
3. Calculate technical indicators and construct input features.
4. Define trend classification labels.
5. Train and evaluate KNN and XGBoost classifiers.
6. Analyze prediction accuracy and feature importance.
7. Compare experimental approaches.

## Project Structure

```text
forex-trend-prediction-ml/
├── README.md
├── notebooks/
│   └── Pred_H4.ipynb
└── .gitignore
```

## Limitations

This project is intended for educational and experimental machine learning research.

Financial time-series prediction is subject to market uncertainty, data leakage risks, and changing market conditions. Classification accuracy does not necessarily translate into profitable trading performance.

No live trading capability or verified financial returns are claimed.

## Author

**Tooraj Jafari**

M.Sc. Artificial Intelligence  
AI & Machine Learning | Python | Software Engineering

## Disclaimer

This project is for educational and research purposes only and does not constitute financial or investment advice.
