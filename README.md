📉 Customer Churn Prediction

🔍 Project Overview

Customer churn refers to customers who stop using a company’s service. Predicting churn in advance helps businesses retain customers, reduce revenue loss, and improve decision-making.

This project builds an end-to-end Machine Learning pipeline to predict whether a telecom customer will churn based on their demographic details, account information, and service usage patterns.

👉 The repository is designed so that anyone can understand the project just by reading this README, without opening the code files.


---

🎯 Objectives

Understand customer behavior using Exploratory Data Analysis (EDA)

Identify key factors influencing customer churn

Build and compare multiple ML models

Evaluate performance using industry-standard metrics

Create a predictive system for real-world use



---

🗂️ Project Structure

customer-churn-prediction/
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks/
│   └── churn_prediction.ipynb
├── images/
│   ├── 01_churn_bar_chart.png
│   ├── 02_churn_by_contract.png
│   ├── 03_tenure_vs_churn.png
│   ├── 04_monthly_charges_vs_churn.png
│   ├── 05_feature_correlation_heatmap.png
│   ├── 06_confusion_matrix.png
│   ├── 07_roc_curve.png
│   └── 08_top10_feature_importance.png
└── README.md


---

📊 Dataset Information

Dataset Name: Telco Customer Churn Dataset

Source: IBM Sample Datasets (Kaggle)

Link: Telco Customer Churn Dataset

Total Records: 7,043 customers

Target Variable: Churn (Yes / No)


Features include:

Customer demographics (gender, senior citizen)

Account information (tenure, contract type, payment method)

Service usage (internet service, streaming, tech support)

Billing information (monthly charges, total charges)



---

🔎 Exploratory Data Analysis (EDA)

### 1️⃣ Overall Churn Distribution
![Churn Distribution](images/01_churn_bar_chart.png)

### 2️⃣ Churn by Contract Type
![Churn by Contract](images/02_churn_by_contract.png)

### 3️⃣ Tenure vs Churn
![Tenure vs Churn](images/03_tenure_vs_churn.png)

### 4️⃣ Monthly Charges vs Churn
![Monthly Charges vs Churn](images/04_monthly_charges_vs_churn.png)

### 5️⃣ Feature Correlation Heatmap
![Feature Correlation Heatmap](images/05_feature_correlation_heatmap.png)

### 6️⃣ Confusion Matrix
![Confusion Matrix](images/06_confusion_matrix.png)

### 7️⃣ ROC Curve
![ROC Curve](images/07_roc_curve.png)

### 8️⃣ Feature Importance (Top 10)
![Feature Importance](images/08_top10_feature_importance.png)

---

🤖 Machine Learning Models Used

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)



---

📈 Model Evaluation Evaluation metrics used:

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve



---

🛠️ How to Run the Project

1. Clone the repository:



git clone https://github.com/rizwanashaik09/customer-churn-prediction.git

2. Navigate to the project folder:



cd customer-churn-prediction

3. Install required Python libraries:



pip install -r requirements.txt

4. Open the Jupyter Notebook:



jupyter notebook notebooks/churn_prediction.ipynb

5. Run the cells sequentially to reproduce EDA, model training, and visualizations.




---

🌟 Future Improvements

Hyperparameter tuning for models

Handling class imbalance using SMOTE

Deploy as a web application using Flask or Streamlit

Real-time prediction system



---

👩‍💻 Author Rizwana Shaik
Aspiring Data Scientist | Machine Learning Enthusiast


---

⭐ If you find this project useful, please give it a star on GitHub!
