⚡ Data-Driven Short-Term Grid Frequency Stability Forecast
🌍 AI-Powered Renewable-Aware Smart Grid Forecasting for Short-Term Frequency Stability


📌 Project Overview

This project develops a short-term grid frequency deviation forecasting system capable of predicting 5-minute and 15-minute ahead grid stability behavior using:

🔋 Core Inputs:
🌤 NASA POWER weather variables
🌞 Solar irradiance proxy
🌬 Wind generation proxy
⚙ Load demand proxy
📈 Historical grid frequency lags
🎯 Objective

Predict deviations from 50 Hz nominal grid frequency before instability occurs by combining:

🤖 AI Models:
🌲 Random Forest
🚀 XGBoost
🧠 LSTM (Long Short-Term Memory)
🧠 Why This Project Matters
⚡ Real-World Relevance:

✔ Renewable intermittency forecasting
✔ Smart grid reliability
✔ Grid balancing analytics
✔ Frequency stability intelligence
✔ Energy transition research

🗂 Repository Structure
grid-frequency-stability-forecast/
│
├── 📂 data/
│   └── grid_frequency_sample.csv
│
├── 📂 outputs/
│   ├── 📂 graphs/
│   │   ├── 01_grid_frequency_timeseries.png
│   │   ├── 02_actual_vs_predicted.png
│   │   ├── 03_residual_distribution.png
│   │   ├── 04_feature_importance.png
│   │   ├── 05_renewable_generation_proxies.png
│   │   ├── 06_load_vs_renewables.png
│   │   ├── 07_prediction_scatter.png
│   │   └── 08_model_performance.png
│   │
│   └── 📂 results/
│       └── model_performance.csv
│
├── 📄 ieee_grid_frequency_stability_paper.pdf
├── 🐍 grid_frequency_forecast.py
├── 🐍 grid_frequency_forecast_live_graphs.py
├── 📦 requirements.txt
└── 📘 README.md
📊 Visual Output Suite (Generated from Actual Code)
📉 1. Grid Frequency Time Series
🔵 Shows real-time fluctuation around 50 Hz baseline
plt.plot(df["timestamp"], df["frequency_hz"])
plt.axhline(50, linestyle="--")
🔍 Insight:

✔ Detects volatility
✔ Observes renewable fluctuation impact

📈 2. Actual vs Predicted Forecast
🟢 Compare true vs ML-predicted deviations
🔍 Insight:

✔ Forecast accuracy
✔ Model trend alignment
✔ Stability prediction capability

📦 3. Residual Error Distribution
🟣 Histogram of prediction error
🔍 Insight:

✔ Bias detection
✔ Overfitting check
✔ Reliability analysis

🌈 4. Feature Importance Ranking
🏆 Top Drivers:
🌞 Solar Proxy
🌬 Wind Proxy
⚙ Load Proxy
🕒 Frequency Lag
importance = model.feature_importances_
🔍 Insight:

✔ Identifies dominant renewable stability drivers

🌤 5. Renewable Generation Proxy Analysis
☀ Solar vs 🌬 Wind:

Visual comparison of generation behavior under weather uncertainty.

⚖ 6. Load vs Renewables Balance
🔍 Insight:

✔ Grid stress periods
✔ Renewable mismatch
✔ Demand-response opportunities

🎯 Model Performance Metrics
📌 Model	📉 MAE	📊 RMSE
🌲 Random Forest	Low	Strong
🚀 XGBoost	Competitive	Robust
🧠 LSTM	Sequential	Deep Forecasting
🚀 Installation
1️⃣ Clone Repository
git clone https://github.com/yourusername/grid-frequency-stability-forecast.git
cd grid-frequency-stability-forecast
2️⃣ Install Dependencies
pip install -r requirements.txt
📦 Requirements
numpy
pandas
matplotlib
scikit-learn
tensorflow
xgboost
▶ Run Project
Standard Run:
python grid_frequency_forecast.py
Live Multi-Graph Run:
python grid_frequency_forecast_live_graphs.py
🔬 Research Strengths
⚙ Technical:

✔ Time-series preprocessing
✔ Feature engineering
✔ LSTM sequence modeling
✔ Ensemble learning
✔ Forecast benchmarking

🌍 Domain:

✔ Renewable systems
✔ Smart grids
✔ Frequency control
✔ Grid resilience

🔮 Future Enhancements
🚀 Next-Level Upgrades:
🔗 Real ENTSO-E API integration
📡 Live frequency feeds
🔋 Battery dispatch optimization
🧠 Transformer forecasting
🌍 Multi-region grid analytics
📚 References

📘 NASA POWER API
📗 ENTSO-E Transparency Platform
📙 XGBoost Research
📕 LSTM Original Paper

👨‍💻 Author
Oihika Arpit
Renewable Energy | Smart Grid | AI for Sustainability
