# ⚡ Data-Driven Short-Term Grid Frequency Stability Forecast  
### AI + Machine Learning for Renewable-Integrated Power System Reliability  

<p align="center">
  <img src="assets/thumbnail.png" alt="Grid Frequency Stability Forecast" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/LSTM-Deep%20Learning-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/XGBoost-ML-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Random%20Forest-Ensemble-darkgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/ENTSO--E-Grid%20Data-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/NASA%20POWER-Weather-yellow?style=for-the-badge">
</p>

---

# 🌍 Abstract  

Modern power grids are increasingly challenged by renewable intermittency, weather variability, and decentralized generation.  
This project develops a **data-driven forecasting framework** to predict **short-term grid frequency deviations (5-min and 15-min horizons)** using:

- ENTSO-E grid frequency data  
- NASA POWER weather features  
- Solar & wind generation proxies  
- Time-series deep learning + ensemble machine learning  

The system compares **LSTM**, **Random Forest**, and **XGBoost** for predictive reliability and operational insight.

---

# 🎯 Project Objectives  

## Primary Goal:
Predict grid frequency instability before it occurs.

## Research Deliverables:
✔ 5-min ahead frequency forecast  
✔ 15-min ahead frequency forecast  
✔ LSTM baseline for temporal sequence learning  
✔ RF/XGBoost benchmark models  
✔ MAE / RMSE / Reliability metrics  
✔ Feature importance ranking  
✔ Forecast visualization suite  

---

# 📌 Why This Project Matters  

As renewable penetration accelerates globally, maintaining frequency stability becomes critical due to:

- Solar intermittency ☀️  
- Wind uncertainty 🌬️  
- Load-generation mismatch ⚡  
- Grid balancing constraints  

This project strongly aligns with:
### Smart Grid | Renewable Integration | Energy Informatics | Sustainable Power Systems | AI for Energy  

---

# 🛰️ Data Sources  

## 1️⃣ ENTSO-E Frequency Data
- Grid frequency deviation records  
- Temporal power system dynamics  

## 2️⃣ NASA POWER API
- Solar irradiance  
- Temperature  
- Wind speed  
- Cloud cover  
- Atmospheric pressure  

## 3️⃣ Renewable Generation Proxies
- Solar output estimates  
- Wind generation approximations  

---
🔬 Feature Engineering
Temporal Features:
Hour of Day
Day of Week
Lagged Frequency Values
Rolling Mean / Std
Weather Features:
Solar Radiation
Wind Speed
Temperature
Pressure
Cloud Cover
Renewable Features:
Estimated Solar Output
Wind Generation Potential
🤖 Models Implemented
🔹 LSTM (Deep Learning)

Purpose: Sequential pattern learning for frequency fluctuations

Strengths:
Captures temporal dependencies
High predictive precision
Effective for dynamic grid systems
🔹 Random Forest

Purpose: Ensemble baseline model

Strengths:
Robust to noise
Easy interpretability
Fast training
🔹 XGBoost

Purpose: High-performance boosting benchmark

Strengths:
Superior feature importance
Handles nonlinear interactions
High forecasting efficiency
📊 Performance Metrics
Metric	Description
MAE	Mean Absolute Error
RMSE	Root Mean Square Error
R² Score	Variance Explanation
Reliability Index	Forecast trustworthiness
📈 Visualization Suite
Forecast Accuracy
results/actual_vs_predicted.png
Residual Diagnostics
results/residual_analysis.png
Feature Importance
results/feature_importance.png
Multi-Model Comparison
results/model_comparison.png
🏆 Sample Insights
Example:
Solar generation volatility strongly impacts afternoon deviations
Wind speed variability influences evening correction
Lagged frequency is among the strongest predictors
📂 Repository Structure
Data-Driven-Short-Term-Grid-Frequency-Stability-Forecast/
│
├── data/
│   ├── entsoe_frequency.csv
│   ├── nasa_weather.csv
│
├── notebooks/
│   ├── preprocessing.ipynb
│   ├── lstm_model.ipynb
│   ├── xgboost_rf.ipynb
│
├── results/
│   ├── actual_vs_predicted.png
│   ├── feature_importance.png
│   ├── residual_analysis.png
│
├── src/
│   ├── data_preprocessing.py
│   ├── train_lstm.py
│   ├── train_xgboost.py
│   ├── evaluate.py
│
├── assets/
│   ├── thumbnail.png
│
└── README.md
🚀 Installation
git clone https://github.com/oihika/Data-Driven-Short-Term-Grid-Frequency-Stability-Forecast.git
cd Data-Driven-Short-Term-Grid-Frequency-Stability-Forecast
pip install -r requirements.txt
▶️ Run the Project
python src/data_preprocessing.py
python src/train_lstm.py
python src/train_xgboost.py
python src/evaluate.py
📚 Academic Value

This project demonstrates:

Technical Skills:

✔ Time-Series Forecasting
✔ LSTM Modeling
✔ Feature Engineering
✔ Energy Data Analytics
✔ Python Research Workflow

Research Readiness:

✔ IEEE-style documentation
✔ Reproducible architecture
✔ Sustainability focus
✔ Grid modernization relevance

🌱 Future Scope
Potential Extensions:
Real-time dashboard deployment
Battery storage optimization
Demand response forecasting
Multi-country grid comparison
Transformer / Attention models
👨‍💻 Author
Oihika Arpit

Electronics & Communication Engineering
AI + Renewable Energy + Smart Grid Research Enthusiast

⭐ If you found this useful:
Star this repository | Fork it | Connect for collaboration

“Building resilient, data-driven solutions for the green energy future.” 🌍⚡


Focus Areas:
Renewable Energy Forecasting
Grid Stability
Energy Storage
AI for Sustainability
