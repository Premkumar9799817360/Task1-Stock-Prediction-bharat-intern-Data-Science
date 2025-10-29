# 📈 STOCK PREDICTION (Bharat Intern)

## 🧠 Project Overview
This project — **Task 1: Stock Prediction (Bharat Intern - Data Science)** — focuses on predicting the **future stock prices** of a chosen company using a **Long Short-Term Memory (LSTM)** model.  
LSTM networks are highly effective for **time series forecasting** as they can capture long-term dependencies in sequential data.

---

## ⚙️ Project Workflow

### 1️⃣ Data Understanding & Preprocessing
- Loaded the stock price dataset of the selected company.  
- Performed **data exploration and correlation analysis** to understand patterns and trends.  
- Applied **feature engineering** and normalization using `MinMaxScaler` to scale data between 0 and 1 for stable LSTM training.

---

### 2️⃣ Time Series Split
Used **TimeSeriesSplit(n_splits=10)** for model validation.  
This ensures that the model is trained and tested on data in **chronological order**, preserving the **time dependency** of stock prices.

---

### 3️⃣ Model Building – LSTM
- Built a **Sequential LSTM Model** using Keras.  
- Added **Dense layers** for output prediction.  
- Used **Adam Optimizer** to minimize loss and improve model performance.  
- Trained the model on scaled time series data to predict future stock closing prices.

---

### 4️⃣ Model Comparison
Along with LSTM, implemented a **Decision Tree Regressor** to compare model performance.  
- The **Decision Tree** provided a baseline for prediction accuracy.  
- The **LSTM** model was finalized as the main predictive model due to its superior performance on sequential data.

---

## 🧩 Technologies Used
| Category | Tools / Libraries |
|-----------|-------------------|
| Programming | Python |
| Libraries | NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow / Keras |
| Model | LSTM, Decision Tree Regressor |
| Optimization | Adam Optimizer |
| Scaling | MinMaxScaler |
| Validation | TimeSeriesSplit (10 splits) |

---
![Stock Prediction Demo](https://github.com/Premkumar9799817360/Task1-Stock-Prediction-bharat-intern-Data-Science/assets/83695512/bc12c493-99c6-40b9-af68-770c6e8bdece)

--- 
## ✅ Conclusion
The project successfully demonstrates **stock price prediction** using **LSTM**.  
By combining **feature engineering**, **time-based validation**, and **deep learning**, it provides an accurate and scalable solution for time series forecasting in financial data.

---
