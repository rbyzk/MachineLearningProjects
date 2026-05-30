# 🛒 Amazon Governance × Risk × Discovery

This project transforms raw Amazon marketplace data into a **decision-support analytics workflow** by combining data governance, satisfaction risk modeling, Voice of Customer analysis, and a lightweight recommendation baseline.

The goal is to make marketplace signals **clean, comparable, explainable, and business-actionable**.

---

## 📌 Project Highlights

* ✅ Cleaned and governed **1,465 Amazon product listings**
* 💰 Parsed INR prices and discount percentages into numeric features
* 🧪 Checked discount integrity using stated vs recalculated discount values
* 📊 Built executive EDA across ratings, prices, discounts, engagement, and categories
* 🤖 Created a **Satisfaction Risk** classifier for products rated below 4.0
* 🧠 Applied **VoC topic modeling** on customer reviews
* 🔍 Built a **content-based recommender** using TF-IDF similarity

---

## 🖼️ Project Preview

![Amazon Governance Risk Discovery](Amazon_Governance_Risk_Discovery/Amazon.png)

---

## 📁 Dataset Overview

| Metric          |             Value |
| --------------- | ----------------: |
| Rows            |             1,465 |
| Columns         |                16 |
| Unique Products |             1,351 |
| Currency        |           INR / ₹ |
| Main Target     | Satisfaction Risk |

Core fields include product names, categories, prices, discounts, ratings, rating counts, and customer reviews.

---

## 🤖 Modeling Approach

The project defines **Satisfaction Risk** as:

```text
rating < 4.0
```

To avoid low-signal observations, only products with:

```text
rating_count >= 50
```

were used for modeling.

Multiple tracks were benchmarked:

* Text Listing-only
* Text Listing + Review
* Structured-only features
* Word + Character TF-IDF uplift model

---

## 🏆 Final Model Performance

The best model was **Uplift LinearSVC** using listing and review text features.

| Metric    | Score |
| --------- | ----: |
| ROC-AUC   | 0.888 |
| PR-AUC    | 0.723 |
| Accuracy  | 0.860 |
| F1-score  | 0.672 |
| Recall    | 0.612 |
| Precision | 0.746 |

---

## 🧠 Key Insights

* Discount fields were mostly consistent after governance checks
* High-volume categories such as **Home & Kitchen** and **Electronics** showed higher satisfaction-risk exposure
* Review text improved risk detection compared to structured-only modeling
* VoC topic modeling revealed recurring themes around quality, charging, battery, display, installation, and usability
* TF-IDF similarity provided a fast and explainable recommendation baseline

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* TF-IDF Vectorization
* LinearSVC
* Random Forest
* LDA Topic Modeling
* Cosine Similarity

---

## 🚀 Business Value

This notebook demonstrates how raw e-commerce data can be converted into a practical analytics product for:

* Data governance
* Discount integrity monitoring
* Product satisfaction risk detection
* Customer review intelligence
* Product discovery and recommendation

---

## ⬇️ Installation & Exploration

```bash
git clone https://github.com/rbyzk/Amazon_Governance_Risk_Discovery.git
cd Amazon_Governance_Risk_Discovery
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

---

## 👩‍💻 About Me

I'm **Beyza Küçük** — a **Data Scientist & Data Analyst**, passionate about building interpretable and business-impact oriented ML solutions.

* 🌐 **Kaggle**: [kaggle.com/beyzakucuk](https://www.kaggle.com/beyzakucuk)
* 💻 **GitHub**: [github.com/rbyzk](https://github.com/rbyzk)

---

✨ If this repository was helpful, please give it a ⭐ star.

---

## 📜 License

This repository is licensed under the **MIT License**.
