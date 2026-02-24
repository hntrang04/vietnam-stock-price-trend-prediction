# Vietnam Stock Price Trend Prediction
<!-- 
![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow%20%7C%20Keras-red)
![Time Series](https://img.shields.io/badge/Task-Time%20Series%20Forecasting-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success) 
-->

**Applying Machine Learning Algorithms to Predict Stock Price Trends in the Stock Market – The Case of Vietnam**

--- 

## 1. Overview

This project applies **Machine Learning and Deep Learning techniques** to forecast the stock price trends of **Vietcombank (VCB)**, a leading financial institution in Vietnam.

Using historical data from 2020 to 2024, the project conducts a comprehensive comparative analysis of **10 different forecasting models**. It contrasts traditional statistical methods against modern AI architectures to determine the most effective strategy for the emerging Vietnamese stock market.

## 2. Objectives

- Analyze historical stock patterns and volatility of VCB stock (2020-2024).
- Implement and compare three categories of models: Statistical, Machine Learning, and Deep Learning.
- Evaluate performance using robust metrics (MAPE, RMSE, MAE) across multiple data split scenarios.
- Identify the optimal model for short-term stock price prediction.

## 3. Methods
### 3.1. Data Pipeline
*   **Source:** Historical data collected from [vn.investing.com](vn.investing.com).
*   **Preprocessing:**
    *   Cleaning & Data Type Conversion.
    *   **Feature Engineering:** Created Lag features (previous day prices), Moving Averages (7-day, 30-day), and Volatility measures.
    *   **Normalization:** Applied `MinMaxScaler` for DL models and `StandardScaler` for others.
*   **Splitting Strategies:** Tested 3 scenarios (65/25/10, 70/20/10, 75/15/10) to ensure robustness.


### 3.2. Model Architectures
**Statistical Models:**
- Linear Regression
- SARIMA / SARIMAX

**Machine Learning:**
- Support Vector Regression (SVR)
- LightGBM (Gradient Boosting)

**Deep Learning:**
- RNN, LSTM, GRU
- Hybrid: CNN-LSTM, CNN-Transformer

## 4. Key Results

- **Linear Regression** achieved the best overall performance with the lowest **MAPE of 0.30%**, demonstrating the strong linear trend in the dataset.
- **GRU** emerged as the best Deep Learning model (**MAPE 0.65%**), outperforming LSTM and RNN in stability.
- Complex hybrid models (CNN-Transformer) showed higher instability compared to simpler statistical approaches for this specific time-series data.

## 5. Tech Stack

- **Programming:** Python
- **Libraries:** Pandas, NumPy, Statsmodels, Scikit-learn
- **Deep Learning:** TensorFlow (Keras)
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 6. Academic Information

- **University:** University of Information Technology – VNU-HCM
- **Faculty:** Information Systems
- **Course:** Business Data Analysis (IS403)
- **Instructor:** M.Sc. Dương Phi Long

## 7. My Contribution

- Contributed to data collection and preprocessing.
- Implementation of RNN, LSTM, and GRU models.
- Primarily responsible for the project report and presentation slides.

## 8. Contact
**Huỳnh Ngọc Trang**
- **Email:** hntrang04@gmail.com
- **LinkedIn:** [Trang Huynh Ngoc](https://www.linkedin.com/in/trang-huynh-ngoc-18128b353/)
