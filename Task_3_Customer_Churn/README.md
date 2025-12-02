Task 3 – Customer Churn Prediction  
CodSoft Machine Learning Internship – Pranish

---

📌 Project Overview
Customer churn is when a customer leaves or stops using a company’s service.  
The goal of this project is to build a Machine Learning model that predicts:

- Exited = 1 → Customer will leave
- Exited = 0 → Customer will stay

This helps companies understand customer behavior and reduce churn.

---

📁 Dataset – Churn_Modelling.csv
The dataset includes 10,000 customer records with features such as:

- CreditScore  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- NumOfProducts  
- HasCrCard  
- IsActiveMember  
- EstimatedSalary  
- Exited (Target variable)

---

🛠️ Steps Performed

1️⃣ Data Loading
Loaded the dataset using Pandas and checked:
- Head  
- Shape  
- Data types  
- Missing values  

2️⃣ Data Cleaning
Removed unnecessary columns:
- RowNumber  
- CustomerId  
- Surname  

These do not impact churn prediction.

3️⃣ Data Encoding
Converted categorical features into numeric form:
- Gender → Label Encoding (Male/Female)
- Geography → One-Hot Encoding (France/Germany/Spain)

4️⃣ Feature Selection
Separated features and target:
- X = All independent columns
- y = Exited (target)

5️⃣ Train/Test Split
Split the data into:
- 80% Training
- 20% Testing

Used scikit-learn’s `train_test_split`.

6️⃣ Model Training
Trained the model using RandomForestClassifier:



Reason for choosing Random Forest:
- High accuracy  
- Handles both numeric & categorical data  
- Low overfitting  
- Fast and stable  

7️⃣ Model Evaluation
Evaluated the model using:
- Accuracy Score
- Confusion Matrix (visualized using heatmap)

---

🎯 Model Performance

⭐ Accuracy Achieved: 87.05%

This is a strong model performance for customer churn prediction.

---

📊 Confusion Matrix
The confusion matrix provides a clear understanding of:
- Correct predictions  
- Incorrect predictions  

Visualized using Seaborn heatmap.

---

 🧰 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Seaborn  
- Matplotlib  
- Google Colab  


---

👨‍💻 Developer  
pranish
Machine Learning Intern – CodSoft  

---

✅ Project Status  
Task 3 Completed Successfully ✔



