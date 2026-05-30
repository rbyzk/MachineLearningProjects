# 👥 Business Context & Decision Questions

This project explores employee attrition through a **decision-support HR analytics workflow**. The notebook connects workforce structure, employee experience signals, workload pressure, compensation, tenure, and career progression patterns to understand where attrition risk is concentrated.

The goal is to move beyond basic reporting and build an interpretable, business-oriented view of **attrition, retention, and workforce risk intelligence**.

---

## 📌 Project Highlights

* ✅ Analyzed **1,470 employee records** across HR, compensation, workload, and career variables
* 📊 Built executive KPIs for attrition rate, overtime share, income, tenure, and promotion lag
* 🔍 Explored attrition patterns across department, job role, overtime, income, tenure, and work-life balance
* 🧾 Created workforce segmentation and executive scorecards
* 🏗️ Engineered people-risk signals such as career friction, workload pressure, and satisfaction composite
* 🤖 Trained interpretable attrition-risk classification models
* 🔎 Explained key attrition drivers using permutation importance and signal-level interpretation
* 👀 Built monitoring-ready risk views for segment tracking and intervention prioritization

---

## 📁 Dataset: HR Attrition Data

* 👥 **Employees**: 1,470
* 📊 **Features**: 35 workforce, compensation, satisfaction, and career variables
* 🎯 **Target**: `Attrition` – whether an employee left the company
* 🧹 **Data Quality**: No missing values and no duplicate rows
* ⚠️ Note: This project is designed for decision-support analytics, not causal inference

---

## 📊 Methods Used

* 📦 Scikit-learn Pipelines
* 🧹 Data quality checks and readiness assessment
* 📈 Executive KPI analysis
* 🔍 Diagnostic EDA
* 🧾 Workforce segmentation and scorecards
* 🏗️ Feature engineering for HR risk signals
* 🤖 Classification models: **Logistic Regression**, **SVC**, **Extra Trees**, and calibrated models
* 📊 ROC-AUC, PR-AUC, F1-score, balanced accuracy, calibration, and lift analysis
* 🔎 Permutation importance for model explainability

---

## 🖼️ Visuals

* Attrition rate by department
* Job role mix and attrition rate
* Overtime vs attrition analysis
* Income and tenure distributions
* Promotion-lag analysis
* Workload pressure heatmaps
* Model ROC and Precision-Recall curves
* Confusion matrix
* Calibration curve
* Risk lift by decile
* Segment monitoring dashboards

---

## 🏆 Model Performance

The champion model was a **Sparse Logistic Regression with Sigmoid Calibration**, selected for its balance between interpretability, discrimination, and operating usability.

| Metric                 | Score |
| ---------------------- | ----: |
| Test ROC-AUC           | 82.6% |
| Test PR-AUC            | 62.6% |
| Test Balanced Accuracy | 0.744 |
| Precision              | 55.7% |
| Recall                 | 57.6% |
| F1-score               | 56.7% |
| Tuned Threshold        |  0.28 |

---

## 🔍 Key Insights

* Attrition pressure is concentrated rather than evenly distributed across the workforce
* Overtime is one of the clearest workload-related attrition signals
* Career friction, promotion lag, satisfaction, and reward positioning repeatedly appear as relevant risk drivers
* Early-career pay pressure and workload pressure segments show elevated attrition rates
* The model improves prioritization while keeping the risk layer interpretable and HR-readable

---

## 🚀 Goal

To demonstrate how HR data can be transformed into a **transparent, interpretable, and monitoring-ready attrition intelligence workflow** — supporting better workforce planning, retention strategy, and targeted intervention design.

---

## ⬇️ Installation & Exploration

📘 Kaggle Notebook: [Business Context & Decision Questions](https://www.kaggle.com/code/beyzakucuk/business-context-decision-questions)

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
