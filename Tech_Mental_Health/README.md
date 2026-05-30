# 🧠 Tech Mental Health — Who Gets Support?

This project analyzes mental health support patterns in the technology workforce using the **OSMI Tech Mental Health Survey**. The notebook explores how workplace support, stigma, demographics, company policies, and work interference relate to treatment uptake and employee well-being.

The goal is to transform survey data into **decision-support insights** for HR, People Analytics, workplace policy, and mental-health strategy.

---

## 📌 Project Highlights

* ✅ Analyzed **1,259 survey responses** from the tech workforce
* 🌍 Covered respondents across **48 countries**
* 🧠 Created custom **SupportScore** and **StigmaScore** indicators
* 📊 Built KPI dashboards around treatment rate, work interference, support, and stigma
* 👥 Segmented employees into **Support × Stigma quadrants**
* 🤖 Trained predictive models to estimate treatment uptake probability
* 🔎 Explained key drivers using permutation importance
* 💡 Converted insights into an executive-ready action plan for workplace mental health support

---

## 📁 Dataset: OSMI Tech Mental Health Survey

* 👥 **Responses**: 1,259
* 📊 **Features**: Demographics, workplace policies, mental-health support, stigma, and treatment indicators
* 🎯 **Target**: `treatment` – whether the respondent sought mental-health treatment
* 🌍 **Coverage**: 48 countries
* ⚠️ Note: This survey is cross-sectional and self-reported, so insights should be interpreted as associations rather than causal effects

---

## 📊 Methods Used

* 🧹 Data cleaning and column standardization
* 📈 Missingness and validity checks
* 🏗️ Feature engineering for **SupportScore** and **StigmaScore**
* 📊 KPI summary and executive dashboards
* 👥 Support × Stigma segmentation
* 🔡 Light text analytics on free-text comments
* 🤖 Predictive modeling with **HistGradientBoosting** and **ElasticNet Logistic Regression**
* 🔎 Permutation importance for explainability

---

## 🖼️ Visuals

* Demographic overview
* Treatment prevalence dashboard
* Work interference analysis
* Workplace support indicators
* SupportScore distribution
* StigmaScore distribution
* Support × Stigma quadrant scorecard
* Model ROC and Precision-Recall curves
* Confusion matrix
* Feature importance table

---

## 🏆 Model Performance

The best-performing model was a tuned **HistGradientBoosting Classifier**, selected for strong discrimination and high recall.

| Metric      | Score |
| ----------- | ----: |
| CV ROC-AUC  | 0.903 |
| CV PR-AUC   | 0.884 |
| CV F1-score | 0.845 |
| CV Recall   | 0.914 |

---

## 🔍 Key Insights

* Treatment uptake is closely linked to reported work interference
* Higher workplace support is associated with better support visibility and lower interference risk
* Higher stigma is associated with lower treatment probability and higher operational friction
* Family history, care options, benefits, coworkers, anonymity, and leave clarity are important decision-support signals
* Support × Stigma quadrants help translate survey results into actionable employee personas

---

## 🚀 Goal

To demonstrate how workplace mental-health survey data can be transformed into a **responsible, interpretable, and action-oriented analytics workflow** — supporting better mental-health policies, stigma reduction, trust-building, and proactive monitoring.

---

## ⬇️ Installation & Exploration

📘 Kaggle Notebook: [Tech Mental Health — Who Gets Support?](https://www.kaggle.com/code/beyzakucuk/tech-mental-health-who-gets-support)

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
