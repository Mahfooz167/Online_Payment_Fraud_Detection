# 💳 Online Payment Fraud Detection using Logistic Regression

<p align="center">
  <img src="banner.png" alt="Online Payment Fraud Detection Banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
  <img src="https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-success?style=for-the-badge">
</p>

---

# 📖 Overview

This project focuses on detecting fraudulent online payment transactions using a **Logistic Regression** machine learning model.

Using a real-world financial transaction dataset, the project demonstrates the complete machine learning workflow—from data preprocessing and feature engineering to model training and evaluation.

The objective is to classify transactions as **fraudulent** or **legitimate**, helping reduce financial losses and improve transaction security.

---

# 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 📂 Repository Contents

```
Online_Payment_Fraud_Detection/
│
├── README.md
├── banner.png
├── Online_Payment_Fraud_Detection.ipynb
└── dataset/
```

---

# 📊 Dataset

The project uses a large real-world online payment transaction dataset containing over **6.3 million** transaction records.

### Features include:

- Transaction Step
- Transaction Type
- Transaction Amount
- Sender Balance
- Receiver Balance
- Fraud Label

Target Variable:

- **isFraud**
  - 0 → Legitimate Transaction
  - 1 → Fraudulent Transaction

---

# ⚙️ Project Workflow

### 1. Data Loading

- Loaded the transaction dataset using Pandas.

### 2. Data Preprocessing

- Removed unnecessary columns
- Encoded categorical variables using One-Hot Encoding
- Prepared numerical features
- Created the final training dataset

### 3. Train-Test Split

- 80% Training Data
- 20% Testing Data

### 4. Model Development

Implemented a **Logistic Regression** classifier using Scikit-learn.

### 5. Model Evaluation

The trained model was evaluated on the test dataset using:

- Accuracy Score
- Confusion Matrix

---

# 📈 Results

The Logistic Regression model achieved a test accuracy of approximately **99.8%** on the evaluation dataset.

A confusion matrix was also generated to visualize model predictions.

> **Note:** Since fraud detection datasets are highly imbalanced, additional evaluation metrics such as Precision, Recall, F1-score, and ROC-AUC should also be considered when assessing model performance.

---

# 🎯 Skills Demonstrated

- Machine Learning
- Logistic Regression
- Fraud Detection
- Data Preprocessing
- Feature Engineering
- One-Hot Encoding
- Data Visualization
- Model Evaluation
- Classification
- Python
- Pandas
- NumPy
- Scikit-learn

---

# 📚 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

# 📈 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Cleaning
- Feature Engineering
- Categorical Encoding
- Machine Learning Classification
- Logistic Regression
- Fraud Detection
- Model Evaluation
- Confusion Matrix Visualization
- End-to-End Machine Learning Workflow

---

# 🔮 Future Improvements

- Hyperparameter Tuning
- Feature Scaling
- SMOTE for Class Imbalance
- Random Forest Classifier
- XGBoost Classifier
- Precision-Recall Analysis
- ROC-AUC Evaluation
- Model Deployment using Streamlit
- API Deployment with FastAPI

---

# 👨‍💻 Author

**Md Mahfooz Alam Ansari**

📧 Email: ansarimahfooz167@gmail.com

🔗 LinkedIn  
https://www.linkedin.com/in/mdmahfoozalamansari/

💻 GitHub  
https://github.com/Mahfooz167

---

## ⭐ Support

If you found this repository helpful, please consider giving it a **Star ⭐**.
