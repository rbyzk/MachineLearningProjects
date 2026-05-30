# 🛒 Amazon Governance × Risk × Discovery

This project transforms raw Amazon marketplace data into a **decision-support analytics workflow** by combining data governance, satisfaction risk modeling, Voice of Customer analysis, and a lightweight recommendation baseline. The goal is to make marketplace signals clean, comparable, explainable, and business-actionable.

---

## 📌 Project Highlights

* ✅ Cleaned and analyzed **1,465 Amazon product listings**
* 💰 Parsed INR prices, discount percentages, ratings, and vote counts into numeric features
* 🧪 Checked discount integrity using stated vs recalculated discount values
* 📊 Built executive EDA across ratings, prices, discounts, engagement, and categories
* 🤖 Trained satisfaction-risk models using structured, listing-text, and review-text features
* 🧠 Applied **VoC Topic Modeling** to discover recurring customer review themes
* 🔍 Built a lightweight **content-based recommender** using TF-IDF similarity

---

## 📁 Dataset: Amazon Product Data

* 🛒 **Rows**: 1,465 product listings
* 📦 **Unique Products**: 1,351 products
* 💰 **Currency**: INR / ₹
* ⭐ **Signals**: prices, discounts, ratings, vote counts, reviews, and categories
* 🎯 **Target**: `at_risk` – products with rating below 4.0
* ⚠️ Note: Products with low engagement were filtered using a vote-count gate for more reliable risk modeling

---

## 📊 Methods Used

* 📦 Scikit-learn Pipelines
* 🧹 Data cleaning and type conversion
* 🧾 Discount governance and integrity checks
* 📊 Executive EDA and category scorecards
* 🔡 TF-IDF vectorization for product and review text
* 🤖 Classification models: **LinearSVC**, **Logistic Regression**, **SGDClassifier**, and **Random Forest**
* 🧠 LDA-based Voice of Customer topic modeling
* 🔍 Content-based recommendation with cosine similarity

---

## 🖼️ Visuals

* Rating and engagement distributions
* Price and discount analysis charts
* Category-level executive scorecards
* Discount integrity diagnostics
* Confusion matrices
* ROC and Precision-Recall curves
* Topic modeling tables
* Recommendation output examples

---

## 🚀 Goal

To demonstrate how raw e-commerce marketplace data can be transformed into a **governed, interpretable, and action-oriented analytics product** — supporting discount integrity monitoring, satisfaction-risk detection, customer review intelligence, and product discovery.

---

## ⬇️ Installation & Exploration

📘 Kaggle Notebook: [Amazon Governance × Risk × Discovery](https://www.kaggle.com/code/beyzakucuk/amazon-governance-risk-discovery)

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
