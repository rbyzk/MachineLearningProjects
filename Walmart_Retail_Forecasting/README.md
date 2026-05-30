# 🛒 Walmart Forecasting — WMAE & Inventory Risk

This project builds an end-to-end retail demand forecasting workflow using Walmart weekly sales data. The notebook forecasts weekly sales at the **Store × Department × Date** level and translates forecast performance into business-readable insights for inventory planning, replenishment, holiday risk, and demand uncertainty.

The goal is to move beyond point forecasting and build a practical **forecast intelligence layer** for retail decision-support.

---

## 📌 Project Highlights

* ✅ Analyzed **421,570 weekly sales records** across Walmart stores and departments
* 🏬 Covered **45 stores**, **81 departments**, and **3,331 Store-Department series**
* 📊 Built executive KPIs for total sales, average weekly sales, holiday share, markdown coverage, and volatility
* 🧹 Prepared train, test, features, and store metadata into modeling-ready datasets
* 🏗️ Engineered calendar, holiday, markdown, lag, rolling, and store-department historical features
* 📉 Evaluated baseline forecasting models such as lag, moving average, and seasonal naive models
* 🤖 Trained a full-scale **LightGBM forecasting model** optimized with **WMAE**
* 🎛️ Applied WMAE-targeted hyperparameter tuning
* 🧩 Built segment-specific models for A/B/C Store-Department sales groups
* 📦 Added quantile forecasting for demand uncertainty and inventory-risk planning
* 🚦 Created forecast diagnostics, watchlists, and inventory action layers

---

## 📁 Dataset: Walmart Sales Forecasting

* 🛒 **Training Rows**: 421,570
* 🏬 **Stores**: 45
* 📦 **Departments**: 81
* 📈 **Forecasting Level**: Store × Department × Date
* 🎯 **Target**: `Weekly_Sales`
* 📅 **Holiday Signal**: Holiday weeks receive higher WMAE weight
* ⚠️ Note: Negative sales were preserved in the raw target and clipped to zero for the clean modeling target

---

## 📊 Methods Used

* 🧹 Data merging and quality checks
* 📈 Executive retail KPI analysis
* 🔍 Diagnostic EDA for holidays, markdowns, stores, departments, and sales concentration
* 📉 Time-series decomposition
* 🏗️ Feature engineering with lag, rolling, calendar, holiday, markdown, and economic signals
* 🧪 Time-based validation strategy
* 📌 Baseline forecasting models
* 🔮 Prophet and SARIMA benchmarks for selected high-volume series
* 🤖 LightGBM regression for full-scale forecasting
* 🎛️ WMAE-targeted hyperparameter tuning
* 🧩 Segment-specific modeling
* 📦 Quantile forecasting and prediction intervals
* 🚦 Forecast diagnostics and inventory risk watchlists

---

## 🖼️ Visuals

* Weekly sales trend
* Holiday peak analysis
* Markdown coverage charts
* Store type and department sales concentration
* Store-Department heatmaps
* Time-series decomposition plots
* Baseline model leaderboard
* Main model validation metrics
* Rolling validation results
* Feature importance chart
* Quantile prediction interval coverage
* Forecast watchlist and risk summary

---

## 🏆 Forecasting Performance

The final workflow compared simple baselines, the main ML model, tuned LightGBM, segment-specific models, and ensemble forecasts using **WMAE**.

| Model                     |  WMAE |
| ------------------------- | ----: |
| Moving Average 4 Baseline | 1,614 |
| Main ML Model             | 1,377 |
| WMAE-Tuned LightGBM       | 1,362 |
| Weighted Ensemble         | 1,301 |

The **Weighted Ensemble** achieved the strongest validation performance by combining global, segment-specific, and baseline forecast signals.

---

## 🔍 Key Insights

* Sales behavior varies significantly across stores, departments, seasons, holidays, and markdown periods
* Holiday weeks require stronger monitoring because WMAE penalizes holiday forecast errors more heavily
* Recent sales history, seasonal lags, rolling statistics, calendar features, and markdown signals are critical forecasting drivers
* High-volume Store-Department combinations deserve closer diagnostic review because errors carry higher inventory and revenue impact
* Quantile intervals help identify where demand uncertainty is high and where safety-stock review may be needed
* Forecast watchlists can translate model error into operational replenishment and inventory-risk actions

---

## 🚀 Goal

To demonstrate how retail sales data can be transformed into a **forecast intelligence and inventory-risk workflow** — supporting demand planning, replenishment prioritization, holiday readiness, and business-aligned forecasting decisions.

---

## ⬇️ Installation & Exploration

📘 Kaggle Notebook: [Walmart Forecasting — WMAE & Inventory Risk](https://www.kaggle.com/code/beyzakucuk/walmart-forecasting-wmae-inventory-risk)

If you found this project insightful or valuable, feel free to **👍 UPVOTE** and leave a comment — your feedback is always welcome!

---

## 🤝 Contributing

Contributions are always welcome!
If you have suggestions, improvements, or want to collaborate, feel free to **fork this repo** and submit a pull request.

---

## 👩‍💻 About Me

I'm **Beyza Küçük** — a **Data Scientist & Data Analyst**, passionate about building ML/DL and analytics solutions that are interpretable, effective, and business-impact oriented.

* 🌐 **Kaggle**: [kaggle.com/beyzakucuk](https://www.kaggle.com/beyzakucuk)
* 💻 **GitHub**: [github.com/rbyzk](https://github.com/rbyzk)

---

✨ If this repository was helpful, please give it a ⭐ star and share it with others.

---

📜 License
This repository is licensed under the **MIT License**. See the LICENSE file for more information.
