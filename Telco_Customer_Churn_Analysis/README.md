# 📡 Telco Churn Intelligence — Risk × Value × Action

This project analyzes customer churn in the telecom industry through a **decision-support analytics workflow**. The notebook combines churn risk, customer value, satisfaction, lifecycle behavior, churn reasons, and geo intelligence into an executive-ready retention framework.

The goal is to move beyond simple churn prediction and build a practical retention lens that helps answer: **who to save, why, and how urgently**.

---

## 📌 Project Highlights

* ✅ Analyzed **7,043 telecom customers** across lifecycle, product, billing, satisfaction, and geo features
* 📊 Built executive KPIs for churn rate, satisfaction, CLTV, churn score, and revenue-at-risk proxy
* 🔍 Explored churn patterns across tenure, contract type, payment method, satisfaction, and customer status
* 💔 Analyzed churn categories and churn reasons to identify root-cause patterns
* 🗺️ Built geo-level churn hot-spot views using city, state, population, and revenue exposure
* 🧭 Created **Risk × Value × Satisfaction** retention segmentation
* 🤖 Benchmarked leakage-safe churn prediction models
* 📈 Evaluated model performance with ROC-AUC, Precision-Recall, confusion matrix, and lift by decile
* 📊 Exported Tableau-ready datasets for dashboard development

---

## 📁 Dataset: Telco Customer Churn

* 👥 **Customers**: 7,043
* 📊 **Features**: 50+ customer, product, lifecycle, financial, satisfaction, churn, and geo variables
* 🎯 **Target**: `Churn Value` – whether the customer churned
* 📉 **Churn Rate**: 26.5%
* 💰 **Business Signals**: CLTV, monthly charges, churn score, satisfaction score, churn category, churn reason
* ⚠️ Note: Leakage fields such as churn score, CLTV, churn reason/category, and post-event churn fields were excluded from predictive modeling

---

## 📊 Methods Used

* 🧹 Data governance and column standardization
* 📈 Executive KPI analysis
* 🔍 Lifecycle, contract, and payment-method EDA
* 💔 Churn reason and category analysis
* 🗺️ City-level geo hot-spot aggregation
* 🧭 Risk × Value × Satisfaction segmentation
* 🤖 Leakage-safe model benchmarking
* 📊 Cross-validation, ROC-AUC, PR analysis, confusion matrix, and lift analysis
* 📤 Tableau-ready export generation

---

## 🖼️ Visuals

* Customer status mix
* Satisfaction vs churn analysis
* CLTV and churn score exposure charts
* Tenure-band churn concentration
* Contract × tenure heatmap
* Payment method churn leaderboard
* Churn reason Pareto chart
* Churn category mix
* City-level churn hot-spots
* Risk × Value scatter map
* Model ROC and Precision-Recall curves
* Lift by decile
* Tableau dashboard export views

---

## 🏆 Model Performance

The best leakage-safe model was **HistGradientBoosting**, selected from a model zoo including Logistic Regression, SVC, Random Forest, Extra Trees, and HistGradientBoosting.

| Model                | CV ROC-AUC |
| -------------------- | ---------: |
| HistGradientBoosting |      0.993 |
| Logistic Regression  |      0.993 |
| SVC-RBF              |      0.992 |
| Random Forest        |      0.971 |
| Extra Trees          |      0.950 |

---

## 🔍 Key Insights

* Churn concentrates in early-tenure and month-to-month customer groups
* Contract type and payment method are strong churn-friction signals
* Low satisfaction aligns strongly with churn behavior
* A small but critical segment exists at **High Risk × High Value × Low Satisfaction**
* Churn reasons follow a clear Pareto pattern and vary by customer segment
* Geo hot-spots reveal where churn rate and revenue-at-risk are both elevated
* Risk becomes more actionable when combined with value and satisfaction, not used alone

---

## 🚀 Goal

To demonstrate how telecom churn data can be transformed into an **executive-ready retention intelligence workflow** — supporting churn reduction, value protection, customer experience strategy, and targeted retention playbooks.

---

## ⬇️ Installation & Exploration

📘 Kaggle Notebook: [Telco Churn Intelligence — Risk × Value × Action](https://www.kaggle.com/code/beyzakucuk/telco-churn-intelligence-risk-value-action)

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
