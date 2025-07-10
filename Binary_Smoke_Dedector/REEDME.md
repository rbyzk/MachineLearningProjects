# 🚬 AUC Boosting: Binary Smoking Detection from Health Checkups

This project tackles the binary classification of smoking status based on health examination records. Using a combination of classical ML models and boosting algorithms, we aim to accurately predict whether an individual is a smoker.

---

## 📊 Dataset Overview

- **Train samples**: 15,000
- **Test samples**: 10,000
- **Total features**: 23 (e.g., blood pressure, vision, cholesterol, liver enzymes)
- **Target variable**: `smoking` (0 = non-smoker, 1 = smoker)
- **Source**: Kaggle Playground Series – Binary Classification

---

## 📌 Project Highlights

✅ Cleaned and explored health check-up data  
📊 Performed correlation analysis and outlier detection  
⚖️ Addressed mild class imbalance  
🧬 Feature selection via ANOVA F-score and Mutual Information  
🤖 Trained multiple models:
- Logistic Regression  
- Random Forest  
- XGBoost  
- LightGBM  
- CatBoost  

📈 Evaluated with metrics:
- Accuracy, F1-Score  
- ROC-AUC  
- Confusion Matrix  

📉 Tuned hyperparameters using GridSearchCV  
📊 Visualized results and model behavior with SHAP

---

## 🔍 Key Features

- 🔬 Medical indicators: blood pressure, cholesterol, glucose, liver enzymes, etc.  
- 👁️ Sensory features: eyesight, hearing  
- ⚖️ Physical metrics: height, weight, waist, hemoglobin  
- 💡 Target behavior: **smoking status**

---

## 🖼️ Visual Insights

- Correlation heatmap of medical features  
- ROC Curve comparisons  
- Feature importance bar plots  
- SHAP summary plots for interpretability  

---

## 🚀 Goal

To apply supervised machine learning techniques for **predicting smoking behavior** using real-world health data, while focusing on **model explainability and ROC-AUC optimization**.

---

## 👩‍💻 Author

**Beyza Küçük**  
*Data Scientist & Data Analyst*

- [GitHub](https://github.com/rbyzk)  
- [Kaggle](https://www.kaggle.com/beyzakucuk)

---

## 📜 License

This project is open-source under the **MIT License**.
