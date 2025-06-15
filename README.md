# 🧮 Footfall Forecasting using Deep Learning & XGBoost

## 📊 Project Overview

This project focuses on **analyzing and forecasting hourly footfall** using machine learning and deep learning techniques. By leveraging historical data in CSV format, the project visualizes footfall trends, identifies hourly patterns by weekday, and utilizes powerful predictive models to forecast future traffic.

---

## 🛠️ Tools & Technologies

- **Python**  
- **Pandas**, **NumPy** – Data manipulation  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Scikit-learn** – Evaluation metrics  
- **TensorFlow/Keras** – LSTM & GRU models  
- **XGBoost** – Gradient boosting model  
- **Jupyter Notebook** – Development environment

---

## 📈 Features

- 📂 Load and preprocess time-series footfall data from CSV  
- 📅 Analyze hourly patterns across weekdays  
- 🔥 Generate heatmaps for time-based traffic visualization  
- 🔮 Build and train:
  - LSTM Model
  - GRU Model
  - XGBoost Model  
- 🤝 Create an **ensemble model** by averaging predictions  
- ✅ Evaluate using **RMSE** and **MAPE**  
- ⏳ Forecast footfall for **future datetimes** using a utility function

---

## 📁 Files

- `Rush_Analysis.ipynb` – Jupyter notebook containing the complete code for data processing, modeling, and visualization
- `footfall_data.csv` – Dataset (assumed)

---

## 🧠 Model Summary

- **LSTM & GRU**: Capture sequential patterns in time-series data with a 24-hour lookback
- **XGBoost**: Models tabular structure with historical time-window features
- **Ensemble**: Averages predictions from all models to improve robustness and accuracy
- **Forecast Function**: Accepts datetime input to predict future footfall

---

## 📌 Use Cases

- Optimize **staff allocation** based on predicted visitor volume  
- Improve **facility and resource planning** in public or retail spaces  
- Enable **data-driven decision-making** for visitor management  

---

