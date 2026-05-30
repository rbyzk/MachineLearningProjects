# ❤️ Heart Failure Prediction — Explainable ML

This project explores heart disease risk prediction using structured clinical data and interpretable machine learning. The notebook combines data quality checks, clinical EDA, feature engineering, model benchmarking, and explainability to transform patient-level signals into actionable health-risk insights.

The goal is to build a transparent and reliable ML workflow for **clinical decision-support analytics**.

---

## 📌 Project Highlights

* ✅ Analyzed **918 patient records** across clinical and cardiovascular features
* 🩺 Explored key risk signals such as age, chest pain type, cholesterol, blood pressure, max heart rate, exercise angina, and ST slope
* 🧹 Handled **zero-coded cholesterol values** as missing-value proxies
* 🏗️ Engineered clinical risk features such as age groups, BP categories, cholesterol flags, risk score, and interaction terms
* 🤖 Benchmarked multiple ML models including **Logistic Regression**, **Random Forest**, **Gradient Boosting**, **XGBoost**, and **LightGBM**
* 🏆 Built a final **Soft Voting Ensemble** using top-performing models
* 📊 Evaluated performance with **accuracy**, **precision**, **recall**, **F1-score**, **ROC-AUC**, and **PR-AUC**
* 🔎 Used **SHAP** for model explainability and clinical interpretation

---

## 📁 Dataset: Heart Disease Clinical Data

* 👥 **Patients**: 918
* 📊 **Features**: 12 clinical variables
* 🎯 **Target**: `HeartDisease` – heart disease outcome
* ⚖️ **Target Balance**: 55.3% positive cases, 44.7% negative cases
* ⚠️ Note: `Cholesterol` contains **172 zero-coded values**, treated as missing-value proxies

Key features include:

* `Age`
* `Sex`
* `ChestPainType`
* `RestingBP`
* `Cholesterol`
* `FastingBS`
* `RestingECG`
* `MaxHR`
* `ExerciseAngina`
* `Oldpeak`
* `ST_Slope`

---

## 📊 Methods Used

* 📦 Scikit-learn Pipelines
* 🧹 Data quality checks and missing-value handling
* 📈 Clinical exploratory data analysis
* 🧪 Chi-square tests for categorical feature relationships
* 🏗️ Feature engineering and interaction features
* 🔁 Stratified train-test split and cross-validation
* 🤖 Model benchmarking and hyperparameter tuning
* 🧠 Soft Voting Ensemble
* 🔎 SHAP-based explainability

---

## 🖼️ Visuals

* Target distribution analysis
* Numerical feature distributions by target
* Categorical feature risk comparisons
* Correlation heatmap
* Model comparison table
* CV PR-AUC executive bar chart
* Confusion matrix
* Classification report
* SHAP feature importance plots

---

## 🏆 Model Performance

The final selected model was a **Soft Voting Ensemble** built from the top-performing models.

| Metric    | Score |
| --------- | ----: |
| ROC-AUC   | 0.935 |
| PR-AUC    | 0.935 |
| Accuracy  | 0.897 |
| F1-score  | 0.907 |
| Recall    | 0.912 |
| Precision | 0.903 |

---

## 🔍 Key Insights

* Heart disease cases showed higher average age and lower maximum heart rate
* `ST_Slope`, `ChestPainType`, and `ExerciseAngina` were highly significant categorical risk indicators
* Zero-coded cholesterol values required explicit handling to avoid misleading model behavior
* Ensemble modeling improved prediction stability and maintained strong clinical interpretability
* SHAP explainability helped translate model outputs into understandable clinical risk drivers

---

## 🚀 Goal

To demonstrate how structured clinical data can be transformed into an **interpretable, high-performing, and decision-support-ready ML workflow** for cardiovascular risk prediction.

---

## ⬇️ Installation & Exploration

📘 Kaggle Notebook: [Heart Failure Prediction — Explainable ML](https://www.kaggle.com/code/beyzakucuk/heart-failure-prediction-explainable-ml)

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
