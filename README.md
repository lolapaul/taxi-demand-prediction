# 🚖 Taxi Demand Prediction

Forecasting the number of taxi orders in the next hour using historical data from Sweet Lift Taxi. This project applies time series analysis and machine learning to support operational planning during peak demand at airports.

---

## 📌 Objective

Build a model to predict the hourly number of taxi orders. The business goal is to improve driver allocation and availability based on forecasted demand, with an RMSE target below 48 on the test set.

---

## 📊 Dataset Description

- **Source:** Sweet Lift Taxi historical order logs
- **File:** `taxi.csv`
- **Target variable:** `num_orders` — number of taxi orders
- **Frequency:** Initially sub-hourly, resampled to hourly intervals

---

## 🔍 Project Workflow

1. **Data Resampling:** Adjusted data into 1-hour intervals
2. **Exploratory Data Analysis:** Trends, seasonality, and outliers
3. **Feature Engineering:** Lag features and rolling statistics
4. **Model Training:**
   - Linear Regression (baseline)
   - LightGBM (tuned)
5. **Model Evaluation:** RMSE on test set

---

## 📈 Key Findings

- Hourly demand shows clear time-of-day and day-of-week patterns.
- LightGBM performed best with tuned hyperparameters.
- Final RMSE on test set met the target of 48.

---

## 📁 Project Structure

```
taxi-demand-prediction/
│
├── proyecto_final_sprint13.ipynb
├── taxi.csv
├── README.md
└── requirements.txt
```



---

## 🛠️ Tools Used

- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- lightgbm
- statsmodels

---

## ✅ Status

✔️ Project completed as part of the **TripleTen Bootcamp** – Sprint: *Time Series Forecasting*

---

## 📌 Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
