# Data Analysis Frameworks Course

This repository contains laboratory assignments for the **Python Frameworks for Data Analysis** course.

## Labs

### Lab 1: Basic ML Pipeline on Tabular Data
- **Location:** `lab1/notebook.ipynb`
- **Dataset:** [Student Depression and Lifestyle 100k Data](https://www.kaggle.com/datasets/aldinwhyudii/student-depression-and-lifestyle-100k-data)
- **Description:** Complete ML pipeline including EDA, data cleaning, feature engineering, and training of Linear Regression (CGPA prediction) and Logistic Regression (Depression classification) models.

### Lab 2: Weather Time-Series Forecasting
- **Location:** `lab2/notebook.ipynb`
- **Dataset:** `lab2/have_fun.xlsx` — multi-sheet Excel with hand-edited weather observations for 6 cities (2019–2025).
- **Description:** Full pipeline from parsing a messy Excel (mojibake, hidden sheets, shifted tables, string NaN sentinels, Cyrillic categorical values) to time-series analysis (STL, ACF/PACF, ADF/KPSS, FFT, STFT, wavelet) and 168-hour multi-step temperature forecasting with Decision Tree, Random Forest and HistGradientBoosting models tuned via Optuna; recursive vs direct strategies are compared on WAPE, MAE, MAPE, directional accuracy and directional R².