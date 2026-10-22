# PM2.5-prediction-jakarta
# Prediction of PM2.5 Concentration in Jakarta Using Statistical and Machine Learning Methods

## 📌 Project Overview

Air pollution is a major environmental concern that affects public health, particularly in urban areas. This project focuses on predicting hourly PM2.5 concentrations in DKI Jakarta using air pollutant and meteorological data collected from five air quality monitoring stations.

Five prediction approaches are developed and compared to identify the model that provides the best prediction performance.

## 🎯 Objectives

- Develop and compare five prediction approaches: SARIMAX, SVR, LightGBM, Hybrid SARIMAX–SVR, and Hybrid SARIMAX–LightGBM.
- Analyze hourly PM2.5 concentration patterns across five monitoring stations in Jakarta.
- Evaluate model performance using MAE, RMSE, and R².
- Identify the best-performing model based on prediction accuracy.

## 📂 Dataset

The dataset consists of hourly observations from January 2020 to December 2024, collected from five air quality monitoring stations in DKI Jakarta.

The data includes:

- **Air Pollutants:** PM2.5, PM10, SO2, CO, O3, and NO2.
- **Meteorological Variables:** Air temperature, solar radiation, rainfall, relative humidity, and wind speed.

**Target Variable:** PM2.5 concentration (µg/m³).

## ⚙️ Project Workflow

1. **Data Collection** — Collect air quality and meteorological data.
2. **Data Understanding** — Explore dataset structure and descriptive statistics.
3. **Data Preprocessing** — Clean the data, handle missing values, and transform data when necessary.
4. **Exploratory Data Analysis (EDA)** — Examine PM2.5 distributions, trends, and temporal patterns.
5. **Data Modeling** — Develop SARIMAX, SVR, LightGBM, and two hybrid models.
6. **Model Evaluation** — Compare prediction performance using MAE, RMSE, and R².
7. **Conclusion** — Determine the best-performing model for each monitoring station.

## 🤖 Models Used

| Model | Description |
|---|---|
| SARIMAX | Statistical time-series model incorporating seasonal patterns and exogenous variables. |
| SVR | Machine learning model based on Support Vector Regression. |
| LightGBM | Gradient boosting algorithm for machine learning prediction. |
| Hybrid SARIMAX–SVR | Combines SARIMAX and SVR predictions. |
| Hybrid SARIMAX–LightGBM | Combines SARIMAX and LightGBM predictions. |

## 📊 Model Evaluation

The models are evaluated using the following metrics:

- **MAE (Mean Absolute Error):** Measures the average absolute prediction error.
- **RMSE (Root Mean Squared Error):** Measures prediction error while penalizing larger errors more heavily.
- **R² (Coefficient of Determination):** Measures how well the model explains the variation in observed PM2.5 concentrations.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- LightGBM
- Google Colab / Jupyter Notebook

## 📌 Project Status

This project was developed as part of a research project on air quality prediction using statistical and machine learning methods.

**Key Outcome:** The final model comparison identifies the most suitable prediction approach based on its evaluation results across the five monitoring stations.
