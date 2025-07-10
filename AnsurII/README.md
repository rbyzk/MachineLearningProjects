# 🧬 Ethnicity Prediction from Body Metrics – ANSUR II

This project explores the predictive power of anthropometric data using the **ANSUR II** dataset — a comprehensive U.S. Army survey that includes over 90 body measurements. The goal is to classify individuals' ethnicity using supervised machine learning models and interpret the results with explainability tools like **SHAP**.

---

## 📌 Project Highlights

- ✅ Cleaned and analyzed **6,000+ samples** of real military anthropometric data  
- ⚖️ Handled **class imbalance** and missing values  
- 🔍 Selected top features using **ANOVA F-score** and **Mutual Information**  
- 🤖 Trained multiple ML models: **Logistic Regression**, **SVM**, **Random Forest**, **XGBoost**, and **LightGBM**  
- 📊 Evaluated performance using **accuracy**, **F1-score**, **ROC-AUC**, and **confusion matrices**  
- 🧠 Visualized model explainability using **SHAP (SHapley Additive exPlanations)**  

---

## 📁 Dataset: ANSUR II

- 👥 **Subjects**: 6,068 U.S. Army personnel  
- 📏 **Measurements**: 93 body metrics (height, limb lengths, head sizes, etc.)  
- 🌍 **Target**: `DODRace` – Ethnic group category  
- ⚠️ Note: 3D scan data not included in public release  

---

## 📊 Methods Used

- 📦 Scikit-learn Pipelines  
- 🧹 Preprocessing (imputation, scaling, encoding)  
- 🔎 Feature Selection  
- 🔁 Cross-validation and model tuning  
- 📈 SHAP for model explainability  

---

## 🖼️ Visuals

- Correlation heatmaps  
- Feature importance plots  
- ROC curves  
- SHAP summary and waterfall plots  

---

## 🚀 Goal

To demonstrate how **anthropometric features** can inform predictive modeling — while ensuring transparency and fairness in classification tasks involving **demographic attributes**.

---

## ⬇️ Installation & Exploration  

📘 Kaggle Notebook: [ AI-SAFE:Smart Safety Monitoring with YOLOv8](https://www.kaggle.com/code/beyzakucuk/ethnicity-prediction-from-body-metrics-ansur-ii)

If you found this project insightful or valuable, feel free to **👍 UPVOTE** and leave a comment — your feedback is always welcome!

---

## 🤝 Contributing  
Contributions are always welcome!  
If you have suggestions, improvements, or want to collaborate, feel free to **fork this repo** and submit a pull request.

---

## 👩‍💻 About Me

I'm **Beyza Küçük** — a **Data Scientist & Data Analyst**, passionate about building ML/DL solutions that are interpretable, effective, and impactful.

- 🌐 **Kaggle**: [kaggle.com/beyzakucuk](https://www.kaggle.com/beyzakucuk)  
- 💻 **GitHub**: [github.com/beyzakucuk](https://github.com/beyzakucuk)  

---
 
✨ If this repository was helpful, please give it a ⭐ star and share it with others.

---

📜 License  
This repository is licensed under the **MIT License**. See the LICENSE file for more information.
