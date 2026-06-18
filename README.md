
# ClimateChange-ML: Forecasting CO₂ Emissions and Global Temperature Anomalies

**ClimateChange-ML** is an open-source Python package and research project developed to support reproducible forecasting of atmospheric CO₂ concentrations and global temperature anomalies using both machine learning and physics-based modeling approaches.

This repository is associated with our published research article and provides the implementation, modeling pipeline, experiments, evaluation results, and reproducible resources used in the study.

---

## Overview

Climate change forecasting requires models that are not only accurate, but also interpretable, scalable, and scientifically meaningful. This project presents a unified modeling framework that combines advanced machine learning models with physically grounded climate modeling approaches.

The study focuses on forecasting global CO₂ levels and temperature anomalies using monthly climate-related time series data from **January 2000 to April 2024**.

The framework integrates:

* Five machine learning models:

  * Long Short-Term Memory Network (LSTM)
  * Convolutional Neural Network (CNN)
  * Extreme Gradient Boosting (XGBoost)
  * Facebook Prophet
  * CNN-LSTM Hybrid Model

* Two physics-based models:

  * Zero-dimensional Energy Balance Model (EBM)
  * Simplified General Circulation Model (GCM) based on NASA GISS concepts

The main goal of the project is to compare data-driven forecasting methods with physically grounded climate models for short-term and long-term climate intelligence.

---

## Key Features

* End-to-end climate forecasting pipeline
* Data preprocessing and temporal filtering
* CO₂ concentration forecasting
* Global temperature anomaly prediction
* Comparison of machine learning and physics-based models
* Short-term and long-term forecasting analysis
* Model evaluation using standard regression metrics
* Visualization and reporting tools
* Pre-trained model weights included
* Reproducible experiments for research and academic use

---

## Models

### Machine Learning Models

The following machine learning models are implemented and evaluated:

| Model            | Purpose                                                            |
| ---------------- | ------------------------------------------------------------------ |
| LSTM             | Sequential time series learning                                    |
| CNN              | Pattern extraction from temporal signals                           |
| XGBoost          | Tree-based nonlinear forecasting                                   |
| Facebook Prophet | Trend and seasonality-based forecasting                            |
| CNN-LSTM Hybrid  | Combined local feature extraction and temporal dependency learning |

### Physics-Based Models

The project also includes simplified physics-based climate models:

| Model                      | Purpose                                                    |
| -------------------------- | ---------------------------------------------------------- |
| Energy Balance Model (EBM) | Long-term climate response simulation                      |
| Simplified GCM             | Climate behavior approximation based on NASA GISS concepts |

These models are used to provide physically meaningful long-term trend estimation and to compare their behavior with purely data-driven forecasting approaches.

---

## Dataset

### Data Sources

The study uses public climate datasets from:

* NOAA — National Oceanic and Atmospheric Administration
* Scripps Institution of Oceanography

### Time Range

Monthly observations from:

```text
2000-01 to 2024-04
```

### Variables

The main variables used in this project include:

| Variable                      | Description                                     |
| ----------------------------- | ----------------------------------------------- |
| Atmospheric CO₂ concentration | Monthly CO₂ concentration values in ppm         |
| Global temperature anomaly    | Monthly global temperature anomaly values in °C |

---

## Methodology

The project follows a structured climate forecasting workflow:

1. Data collection from public climate data sources
2. Data cleaning and preprocessing
3. Temporal filtering from January 2000 to April 2024
4. Feature preparation for machine learning models
5. Model training and validation
6. Forecasting CO₂ concentrations and temperature anomalies
7. Evaluation using regression metrics
8. Comparison between machine learning and physics-based models
9. Visualization of predicted vs observed trends
10. Interpretation of forecasting behavior across different time horizons

---

## Results

### CO₂ Forecasting

For atmospheric CO₂ forecasting, **Facebook Prophet** achieved the best performance among the evaluated machine learning models.

```text
Best model: Facebook Prophet
RMSE: 0.035
```

Prophet showed strong performance due to its ability to model trend and seasonal behavior in monthly CO₂ concentration data.

### Temperature Anomaly Prediction

For global temperature anomaly prediction, the **LSTM model** achieved the best performance.

```text
Best model: LSTM
RMSE: 0.086
```

The LSTM model performed well because of its ability to capture temporal dependencies and nonlinear changes in climate-related time series.

### Physics-Based Models

The physics-based models provided robust long-term climate trend estimation, although their short-term forecasting accuracy was lower compared with machine learning models.

```text
Physics-based models RMSE: approximately 0.12–0.15
```

These models remain valuable because they provide physically interpretable behavior and support long-term climate reasoning.


## Evaluation Metrics

The models are evaluated using standard regression metrics, including:

* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Forecast visualization against observed values

---

## Research Contribution

This project contributes a reproducible and comparative framework for climate-related time series forecasting by combining:

* Machine learning-based forecasting
* Deep learning-based temporal modeling
* Physics-based climate simulation
* Comparative evaluation across CO₂ and temperature anomaly prediction
* Interpretable forecasting for climate intelligence applications

The integration of data-driven and physically grounded models provides a broader understanding of climate forecasting performance across different temporal horizons.

---

## Citation

If you use this repository, code, or results in your research, please cite our published article:

```bibtex
@article{your_citation_key,
  title={Predicting Climate Change: A Comparative Analysis of Time Series Models for CO2 Concentrations and Temperature Anomalies},
  journal={Environmental Modelling & Software},
  year={2025},
  doi={https://doi.org/10.1016/j.envsoft.2025.106533}
}
```

Please replace the citation information with the final published article details.


## Keywords

Climate Change, CO₂ Forecasting, Temperature Anomaly Prediction, Machine Learning, Deep Learning, LSTM, CNN, XGBoost, Prophet, CNN-LSTM, Energy Balance Model, General Circulation Model, Climate Intelligence, Time Series Forecasting

