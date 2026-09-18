# CREDIT-CARD-FRAUD-DETECTION
A machine learning project that detects fraudulent credit card transactions by analyzing transaction patterns and classifying them as legitimate or fraudulent. The project uses data preprocessing, exploratory data analysis, and machine learning algorithms to improve fraud detection and help reduce financial losses.
# 💳 Credit Card Fraud Detection

## 📌 Project Overview

Credit Card Fraud Detection is a Machine Learning project designed to identify fraudulent credit card transactions. The system analyzes transaction data and classifies each transaction as either **legitimate** or **fraudulent**.

The project focuses on building a reliable classification model while addressing the major challenge of **imbalanced datasets**, where fraudulent transactions are much fewer than normal transactions.

## 🎯 Objectives

* Detect fraudulent credit card transactions.
* Perform data preprocessing and exploratory data analysis.
* Handle class imbalance effectively.
* Train and compare different Machine Learning models.
* Evaluate model performance using suitable classification metrics.
* Reduce the chances of missing fraudulent transactions.

## 📊 Dataset

The dataset contains credit card transaction records with numerical and anonymized features.

The target variable is:

* `0` → Legitimate Transaction
* `1` → Fraudulent Transaction

> **Note:** The dataset is highly imbalanced because genuine transactions greatly outnumber fraudulent transactions.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Imbalanced-learn**
* **Jupyter Notebook**

## 🤖 Machine Learning Models

The following algorithms can be used for fraud detection:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

The models are compared using multiple evaluation metrics to identify the most suitable model.

## ⚙️ Project Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Scaling
   ↓
Handle Class Imbalance
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Fraud Prediction
```

## ⚠️ Handling Class Imbalance

Since fraudulent transactions represent only a small portion of the dataset, accuracy alone is not sufficient to evaluate the model.

Techniques such as **SMOTE** and **class weighting** can be used to address class imbalance.

## 📈 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

**Recall is particularly important** because failing to detect a fraudulent transaction can have significant consequences.

## 🔍 Prediction

The trained model predicts whether a transaction is:

```text
0 → Legitimate
1 → Fraudulent
```

## 🚀 Future Enhancements

* Develop a Streamlit web application.
* Add real-time fraud detection.
* Implement advanced ensemble models.
* Add transaction monitoring and alert systems.
* Improve model performance using hyperparameter tuning.
* Deploy the model using a cloud platform.

## 📂 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── dataset/
│   └── creditcard.csv
│
├── notebook/
│   └── fraud_detection.ipynb
│
├── models/
│   └── fraud_model.pkl
│
├── src/
│   └── fraud_detection.py
│
├── requirements.txt
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
```

### 2. Navigate to the project

```bash
cd Credit-Card-Fraud-Detection
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the `fraud_detection.ipynb` notebook and run the cells.

## 👩‍💻 Author

**vippalasubhashini**

B.Tech AI & ML Student
Interested in Artificial Intelligence, Machine Learning, and Deep Learning.

## ⭐ Conclusion

This project demonstrates how Machine Learning can be applied to detect fraudulent credit card transactions. By combining data preprocessing, class-imbalance handling, classification algorithms, and appropriate evaluation metrics, the system can help identify potentially fraudulent transactions effectively.
