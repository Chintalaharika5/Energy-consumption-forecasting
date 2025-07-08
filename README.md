# ⚡ Energy Consumption Forecasting using Machine Learning


## 🔍 Overview
This project aims to forecast future energy consumption using historical data and machine learning models. Accurate energy prediction helps in effective resource management, load balancing, and policy planning for sustainable energy systems.

---

## 🎯 Objectives
- Analyze historical energy consumption patterns
- Build predictive models using machine learning
- Evaluate and compare the performance of models
- Forecast future energy usage with high accuracy

---

## 🧠 Problem Statement
Unpredictable energy demands can lead to overloading, wastage, or inefficiencies in energy distribution. This project focuses on building a predictive model that can estimate future energy consumption based on time-series data and relevant influencing factors.

---

## 🧰 Technologies Used
- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost, statsmodels  
- **Model Types**: Linear Regression, XGBoost Regressor, ARIMA, LSTM (optional advanced)  
- **Jupyter Notebook** for model training and visualization  
- **CSV Dataset** (Daily/Hourly/Monthly Energy Consumption Data)

---

## 📊 Dataset
- **Source**: [UCI Energy Dataset](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction) / [Kaggle Energy Datasets](https://www.kaggle.com/datasets)
- **Features**:
  - Timestamp  
  - Temperature  
  - Humidity  
  - Energy usage (kWh)  
  - Other optional features (e.g., wind speed, day of the week)

---

## 🔁 Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Feature extraction (hour, day, month)
   - Scaling

2. **Exploratory Data Analysis**
   - Correlation heatmaps
   - Trend & seasonality plots

3. **Model Building**
   - Split data into training/testing sets
   - Train baseline and advanced models
   - Fine-tune hyperparameters

4. **Evaluation**
   - Metrics: MAE, RMSE, R² Score
   - Visualization of predicted vs actual

5. **Forecasting**
   - Predict future energy usage for next N days/hours
   - Export prediction results

---

## 📌 Example Output

```
Date        | Predicted (kWh) | Actual (kWh)
------------|------------------|--------------
2025-06-01  | 340.25           | 342.00
2025-06-02  | 355.10           | 357.25
```

---

## 📈 Visualization
- Time-series line plot of actual vs predicted values  
- Feature importance graph (for XGBoost)  
- Residual error plots  



---

## ✅ Results
- **Best Model**: XGBoost Regressor  
- **RMSE**: 18.65 kWh  
- **MAE**: 14.23 kWh  
- **R² Score**: 0.92

---

## 🔮 Future Scope
- Add LSTM model for sequence-based deep learning
- Include real-time data ingestion from IoT sensors
- Deploy as a Flask app for live forecasting

---

## 🧑‍💻 Author
**Chintala Harika**  
Email: [chintalaharik5@gmail.com](mailto:chintalaharik5@gmail.com)  
GitHub: [github.com/Chintalaharika5](https://github.com/Chintalaharika5)
