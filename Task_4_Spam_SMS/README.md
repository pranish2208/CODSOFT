📌 Task 4 – Spam SMS Detection

 CodSoft Machine Learning Internship – Pranish

---

📝 Project Overview

This project aims to classify SMS messages as **Spam** or **Ham (Not Spam)** using Machine Learning.
It helps in filtering unwanted messages and preventing fraud/scam communication.

---

📂 Dataset – `spam.csv`

The dataset contains SMS text messages labeled as:

* ham → Normal message
* spam → Unwanted / fraudulent message
⭐ Key Columns:

* v1 → Label (ham/spam)
* v2 → SMS text message

---

🛠️ Steps Performed

1️⃣ Data Loading

Loaded the dataset and inspected:

* Shape
* Head
* Missing values

2️⃣ Data Cleaning

Performed:

* Renamed columns → (`label`, `message`)
* Removed unused extra columns
* Checked for duplicates
* Converted labels to binary (ham = 0, spam = 1)

3️⃣ Text Preprocessing

Cleaned message text using NLP steps:

* Lowercasing
* Removing punctuation
* Removing stopwords
* Lemmatization
* Tokenizing

4️⃣ Feature Extraction

Used TF-IDF Vectorization to convert text into numerical features suitable for machine learning.

5️⃣ Train/Test Split

* 80% → Training
* 20% → Testing

---

🤖 Model Used

Multinomial Naive Bayes

* Works extremely well for text classification
* Fast and lightweight
* Ideal for SPAM detection tasks

---

📊 Model Performance

 ⭐ Accuracy Achieved: **97.84%**

This is a high-performance SMS spam classifier.

 Additional Metrics:

* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

🔍 Confusion Matrix Meaning:

* TP: Messages correctly predicted as spam
* TN:Messages correctly predicted as ham
* FP:Ham messages wrongly predicted as spam
* FN:Spam messages wrongly predicted as ham

---

 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* NLTK
* Seaborn
* Matplotlib
* Google Colab



---

👨‍💻 Developer

Pranish
Machine Learning Intern – CodSoft


Just tell me!

