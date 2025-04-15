# 🔧 Predictive Maintenance & Engine Health Classification – Dash + ML

This project delivers a comprehensive **Predictive Maintenance solution** using multiple **Machine Learning models** and the **NASA Turbofan Engine Degradation Dataset**. It predicts the **Remaining Useful Life (RUL)**, estimates **30-day failure probabilities**, and performs **engine health classification** via an interactive **Dash web app**.

---

## 📌 Key Features

- 🧠 Uses various ML models for accurate RUL prediction
- 📉 Predicts failure probability over the next 30 days
- 📊 Classifies engines into health categories based on life ratio
- 📈 Visualizes trends, forecasts, and classifications in a Dash app
- ⚡ Interactive & responsive user interface for exploration

---

## 🚀 Project Goals

- Predict **Remaining Useful Life (RUL)** for each engine unit
- Estimate **failure probability** over a defined future horizon (30 days)
- Classify engines based on **life ratio buckets**
- Provide a role-based dashboard for **engineers, analysts, and operations teams**

---

## 📂 Dataset

**Source**: NASA’s CMAPSS – Turbofan Engine Degradation Simulation Dataset  
**Data Includes**:
- Engine ID, cycle count
- Sensor readings (21+ features)
- Operational settings
- Actual failure time for supervised learning

> Data was preprocessed and used to compute target labels for:
> - RUL (continuous regression)
> - Failure Probability (per day)
> - Life Ratio Classification (low, medium, high risk)

---

## 🧠 ML Models Used

- 📈 Linear Regression & XGBoost for RUL Prediction
- 🧮 Logistic Regression & Random Forest for 30-day Failure Probability
- 🧠 SVM / Decision Tree / XGBoost Classifier for Life Ratio Classification
- ✅ Trained using `scikit-learn`, `xgboost`, and custom pipelines

---

## 📊 Dash Interface Features

- 📤 Upload and test new engine data
- 📉 RUL Prediction with trend plots
- 📆 30-Day Failure Rate Visualization
- 🟢 Engine Life Ratio Classification Output
- 📊 Multi-tab layout for different analytics

---

## 📈 Sample Outputs
RUL Trend Graph for Each Engine

Failure Probability Line Chart (Next 30 Days)

Health Class Indicator: High Risk, Medium, or Low

---
