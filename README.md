

ClimateChange-ML: Forecasting CO₂ Emissions and Global Temperature Anomalies

ClimateChange-ML is an open-source Python package and research project that integrates machine learning and physics-based models to forecast CO₂ emissions and global temperature anomalies. This project aims to provide accurate, interpretable, and scalable forecasts using both data-driven and physically grounded approaches.



Overview

This study presents a unified modeling framework combining:

Five advanced ML models (LSTM, CNN, XGBoost, Facebook Prophet, CNN-LSTM Hybrid)

Two physics-based models (Energy Balance Model, General Circulation Model from NASA GISS)


The goal is to forecast global CO₂ levels and temperature anomalies between January 2000 to April 2024, using high-quality public datasets.

Features

End-to-end modeling pipeline: preprocessing, training, evaluation

Comparison of data-driven vs physics-based models

Integrated visualization and reporting tools

Pre-trained model weights included

Interpretability and forecasting across short and long temporal horizons


Models

Machine Learning Models:

Long Short-Term Memory (LSTM)

Convolutional Neural Network (CNN)

Extreme Gradient Boosting (XGBoost)

Facebook Prophet

CNN-LSTM Hybrid


Physics-Based Models:

Zero-dimensional Energy Balance Model (EBM)

Simplified General Circulation Model (GCM) based on NASA GISS


Dataset

Source:

NOAA (National Oceanic and Atmospheric Administration)

Scripps Institution of Oceanography


Range:

Monthly data from 2000-01 to 2024-04


Variables:

Atmospheric CO₂ concentrations (ppm)

Global temperature anomalies (°C)



Results

CO₂ Emission Forecasting:

Facebook Prophet achieved best performance (RMSE = 0.035)


Temperature Anomaly Prediction:

LSTM model outperformed others (RMSE = 0.086)


Physics-Based Models:

Provided robust long-term trends (RMSE ≈ 0.12–0.15), but lower short-term accuracy
