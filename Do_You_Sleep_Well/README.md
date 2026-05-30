# 😴 Do You Sleep Well? — A Data Story

This project explores how lifestyle, health, and demographic factors relate to sleep quality and sleep disorder risk. Using the **Sleep Health & Lifestyle** dataset, the notebook builds a clear data story around stress, activity, BMI, occupation, and sleep outcomes.

The goal is to turn sleep-related data into **interpretable and decision-ready insights** for wellness, HR analytics, and digital-health use cases.

---

## 📌 Project Highlights

* ✅ Analyzed **374 individuals** across sleep, lifestyle, health, and demographic features
* 😴 Explored sleep duration, sleep quality, insomnia, and sleep apnea patterns
* 📊 Built visual EDA around stress, activity, BMI, occupation, and cardio-health signals
* 👥 Created transparent sleeper segments: **Healthy**, **Intermediate**, and **High-Risk**
* 🤖 Trained a baseline model to predict sleep disorder risk
* 📈 Evaluated model performance using **ROC-AUC**, classification metrics, and feature importance
* 💡 Converted insights into actionable recommendations for wellness and health strategy

---

## 📁 Dataset: Sleep Health & Lifestyle

* 👥 **Subjects**: 374 individuals
* 📊 **Features**: 13 lifestyle, health, sleep, and demographic variables
* 🎯 **Target**: `Has Disorder` – whether the person has insomnia or sleep apnea
* 😴 **Sleep Outcomes**: Sleep duration, sleep quality, and sleep disorder status
* ⚠️ Note: Missing sleep disorder values were treated as **None**, representing no diagnosed disorder in this dataset

---

## 📊 Methods Used

* 🧹 Data cleaning and validation
* 🩺 Blood pressure feature extraction
* 👥 Rule-based sleeper segmentation
* 📊 Exploratory Data Analysis
* 📈 Correlation and group-level analysis
* 🤖 Gradient Boosting baseline model
* 🔎 Feature importance interpretation

---

## 🖼️ Visuals

* Sleep disorder distribution
* Sleep duration vs sleep quality charts
* Stress vs sleep quality analysis
* BMI category and sleep disorder prevalence
* Occupation-level sleep risk profiles
* Sleeper segment comparison charts
* ROC curve and feature importance plot

---

## 🏆 Model Performance

A baseline **Gradient Boosting Classifier** was trained to predict whether an individual has a sleep disorder.

| Metric    | Score |
| --------- | ----: |
| ROC-AUC   | 0.967 |
| Accuracy  | 0.960 |
| Precision | 0.967 |
| Recall    | 0.935 |
| F1-score  | 0.951 |

---

## 🔍 Key Insights

* High stress is strongly associated with shorter sleep duration and lower sleep quality
* Higher physical activity and daily steps tend to align with better sleep quality
* Overweight and obese groups show higher sleep disorder prevalence
* Certain occupations show concentrated sleep-risk patterns
* High-risk sleepers are characterized by shorter sleep, lower quality, higher stress, and elevated disorder rates

---

## 🚀 Goal

To demonstrate how a compact lifestyle dataset can be transformed into a **clear, visual, and actionable data story** — helping identify sleep-risk patterns and support wellness-focused decision-making.

---

## ⬇️ Installation & Exploration

📘 Kaggle Notebook: [Do You Sleep Well? — A Data Story](https://www.kaggle.com/code/beyzakucuk/do-you-sleep-well-a-data-story)

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
