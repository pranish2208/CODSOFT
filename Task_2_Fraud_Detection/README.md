📌 Task 2 — Credit Card Fraud Detection

CodSoft Machine Learning Internship

📖 Overview

This project focuses on detecting fraudulent credit card transactions using machine learning.
The goal is to analyze transaction patterns and classify whether a transaction is **fraud** or **not fraud**.

The model uses cleaned features such as:

* Transaction amount (`amt`)
* Transaction location (`lat`, `long`)
* Merchant location (`merch_lat`, `merch_long`)

And predicts:

* `is_fraud` → **1 = Fraud**, **0 = Legitimate

---

📊 Dataset

The dataset used is from **Kaggle – Fraud Detection Dataset**.
It contains:

* 1000 customers
* Legitimate + fraudulent transactions
* Merchant information
* Time & location data

Files:

* `fraudTrain.csv`
* `fraudTest.csv`

---

🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Random Forest Classifier
* Seaborn / Matplotlib
* Google Colab

---

🔧 Project Workflow

1️⃣ Data Loading

Loaded training & test dataset using Pandas.

2️⃣ Data Cleaning

Kept only numeric and important columns:

* `amt`, `lat`, `long`, `merch_lat`, `merch_long`, `is_fraud`

Removed missing values.

3️⃣ Feature Selection

Split into:

* **X** → features
* **y** → target (`is_fraud`)

4️⃣ Model Training

Used:

```
RandomForestClassifier(n_estimators=200, random_state=42)
```

5️⃣ Model Evaluation

* **Accuracy:** 99.64%
* Confusion Matrix shows very few fraud misses.

---

🎯 Results

| Metric         | Score         |
| -------------- | ------------- |
| Accuracy       | **99.64%**    |
| Model          | Random Forest |
| Fraud Detected | ✔ Yes         |

The model performs extremely well for fraud prediction.

---

👨‍💻 Developer

Pranish
CodSoft Machine Learning Intern


Just tell me!
