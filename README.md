# Prediction of PM₂.₅ in Megacity Jakarta using statistical and machine learning methods

## 📌 Project Overview

Air pollution is a major environmental concern that affects public health, particularly in urban areas. This project focuses on predicting hourly PM2.5 concentrations in DKI Jakarta using air pollutant and meteorological data collected from five air quality monitoring stations.

Five prediction approaches are developed and compared to identify the model that provides the best prediction performance.

## 🎯 Objectives

- Develop and compare five prediction approaches: SARIMAX, SVR, LightGBM, Hybrid SARIMAX–SVR, and Hybrid SARIMAX–LightGBM.
- Analyze hourly PM2.5 concentration patterns across five monitoring stations in Jakarta.
- Evaluate model performance using MAE, RMSE, and R².
- Identify the best-performing model based on prediction accuracy.

## 📂 Dataset

### Study Area and Period

The dataset consists of hourly observations collected from five air quality monitoring stations in DKI Jakarta, Indonesia.

- **Study Period:** January 1, 2020 – December 31, 2024
- **Temporal Resolution:** Hourly
- **Study Area:** DKI Jakarta, Indonesia
- **Target Variable:** PM2.5 concentration (µg/m³)

### Air Quality Data

Air quality data were obtained from the DKI Jakarta Environmental Agency (Dinas Lingkungan Hidup DKI Jakarta).

The pollutant variables include:

- PM2.5
- PM10
- SO2
- CO
- O3
- NO2

### Meteorological Data

Meteorological data were obtained from ERA5, a global atmospheric reanalysis dataset.

The meteorological variables include:

- **Air Temperature (°C)**
- **Solar Radiation (W/m²)**
- **Rainfall (mm)**
- **Relative Humidity (%)**
- **Wind Speed (m/s)**

These variables provide additional information about weather conditions that may influence PM2.5 concentrations.

### Monitoring Stations

The study covers five monitoring stations in DKI Jakarta:

1. DKI1 – Bundaran HI
2. DKI2 – Kelapa Gading
3. DKI3 – Jagakarsa
4. DKI4 – Lubang Buaya
5. DKI5 - Kebon Jeruk

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
