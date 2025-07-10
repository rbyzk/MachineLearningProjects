# 🔥 AUC Boosting: Binary Smoking Detection from Health Checkups

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

⬇️ Installation  
To explore this notebook online, visit my Kaggle profile.  
If you find this project helpful or inspiring, please give it an **👍 UPVOTE** and join the discussion!

📘 Kaggle Notebook: [AUC Boosting – Binary Smoking Detection](https://www.kaggle.com/code/beyzakucuk/auc-boosting-binary-smoking-detection)


---

🤝 Contributing  
Contributions are always welcome!  
If you have suggestions, improvements, or want to collaborate, feel free to **fork this repo** and submit a pull request.

---

🌱 About Me  
I'm **Beyza Küçük** — a **Data Scientist & Data Analyst**, passionate about building ML/DL solutions that are interpretable, effective, and impactful.

📬 You can find more about me and my work through the following platforms:

- 🌐 **Kaggle**: [kaggle.com/beyzakucuk](https://www.kaggle.com/beyzakucuk)  
- 💻 **GitHub**: [github.com/beyzakucuk](https://github.com/beyzakucuk)  

---

🎯 Let’s grow together in the world of machine learning and AI.  
✨ If this repository was helpful, please give it a ⭐ star and share it with others.

Keep coding and learning! 💡🚀

---

📜 License  
This repository is licensed under the **MIT License**. See the LICENSE file for more information.
