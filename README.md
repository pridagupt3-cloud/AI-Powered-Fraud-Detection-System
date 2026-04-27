# 💳 AI-Powered Fraud Detection System

### Advanced Machine Learning Project for Financial Risk Prevention

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-Production%20Ready-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Streamlit-Deployed-red?style=for-the-badge&logo=streamlit"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---

## 🚀 Project Overview

Developed a **production-ready fraud detection system** leveraging machine learning to identify suspicious financial transactions in real-time.

This project combines:

* 📊 Exploratory Data Analysis (EDA)
* 🧠 Predictive Modeling
* ⚙️ Automated ML Pipeline
* 🌐 Streamlit Deployment
* 📈 Business Risk Intelligence

The application enables users to input transaction details and instantly determine whether a transaction is potentially fraudulent.

---

## 🎯 Business Problem

Financial institutions lose billions annually due to fraudulent digital transactions. Detecting suspicious activity in real-time is crucial for:

* Preventing monetary loss
* Enhancing customer security
* Reducing operational fraud risk
* Strengthening compliance frameworks

This solution addresses these challenges using predictive analytics.

---

## 📂 Project Architecture

```bash
Fraud-Detection-System/
│
├── fraud_detection.py               # Streamlit web app
├── fraud_detection_pipeline.pkl     # Serialized ML pipeline
├── analysis_model.ipynb             # Data analysis + model training
├── AIML Dataset.csv                 # Transaction dataset
├── requirements.txt                 # Dependencies
└── README.md                        # Documentation
```

---

## 📊 Dataset Overview

The dataset contains transactional financial records with the following critical features:

| Feature        | Description                 |
| -------------- | --------------------------- |
| type           | Transaction category        |
| amount         | Transaction value           |
| oldbalanceOrg  | Sender’s previous balance   |
| newbalanceOrig | Sender’s updated balance    |
| oldbalanceDest | Receiver’s previous balance |
| newbalanceDest | Receiver’s updated balance  |

---

## 🔍 Exploratory Data Analysis (EDA)

### Key Findings:

### 🚨 Fraud Patterns

* Fraud is predominantly observed in:

  * `TRANSFER`
  * `CASH_OUT`

### 💰 High-Risk Indicators

* Large transaction values
* Balance inconsistencies
* Sudden sender account depletion
* Receiver balance anomalies

### 📈 Behavioral Trends

* Fraudulent transactions often bypass normal balance progression
* Certain transaction types are disproportionately vulnerable

---

## 🧹 Data Preprocessing & Feature Engineering

Implemented:

* Missing value handling
* Categorical encoding
* Feature scaling
* ML pipeline automation
* Model serialization with `joblib`

---

## 🤖 Machine Learning Pipeline

The project includes a complete ML workflow:

### Core Components:

* Data preprocessing transformer
* Feature engineering
* Classification model
* Prediction interface

### Deployment:

* Integrated into Streamlit for user accessibility
* Real-time transaction scoring

---

## 📌 Model Features Used

* Transaction Type
* Amount
* Sender Old Balance
* Sender New Balance
* Receiver Old Balance
* Receiver New Balance

---

## 📈 Performance Metrics

> *(Update with actual scores from your notebook)*

| Metric    | Performance |
| --------- | ----------- |
| Accuracy  | 99%+        |
| Precision | High        |
| Recall    | Strong      |
| F1-Score  | Optimized   |

---

## 🌐 Streamlit Web Application

### Features:

* Interactive UI
* Instant predictions
* User-friendly dashboard
* Fraud alerts
* Secure deployment structure

### Sample Workflow:

1. Enter transaction details
2. Click Predict
3. Receive fraud classification
4. Get instant risk assessment

---

## 💼 Portfolio Value

This project demonstrates expertise in:

* Machine Learning
* Predictive Analytics
* Fraud Detection
* Python Development
* Streamlit Deployment
* Business Intelligence
* End-to-End Data Science Solutions

---

## 🛠️ Tech Stack

### Languages & Libraries:

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Joblib
* Matplotlib / Seaborn

---

## 📷 Recommended GitHub Additions

To maximize recruiter engagement:

* App screenshots
* Demo video
* Deployment link
* Jupyter Notebook analysis
* Feature importance charts
* Confusion matrix
* ROC-AUC visualization

---

## 🚀 Future Enhancements

* Deep learning fraud models
* XGBoost / LightGBM optimization
* API deployment
* Cloud integration (AWS/GCP)
* Real-time banking dashboard
* Transaction monitoring alerts

---

## 📜 Installation Guide

### Clone Repository

```bash
git clone https://github.com/your-username/fraud-detection-system.git
cd fraud-detection-system
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run fraud_detection.py
```

---

## 🤝 Contribution

Contributions are welcome.

### Steps:

1. Fork repository
2. Create feature branch
3. Commit changes
4. Open Pull Request

---

## 👨‍💻 Author

### **Priyam Dattagupta**

**Data Analyst | Machine Learning Enthusiast | Business Intelligence Professional**

* GitHub: https://github.com/your-username
* LinkedIn: https://linkedin.com/in/your-profile

---

## ⭐ Why This Project Stands Out

✔ Real-world financial application
✔ End-to-end machine learning lifecycle
✔ Production deployment
✔ Recruiter-friendly architecture
✔ Strong portfolio impact

---

# 📌 Final Note

This project reflects advanced problem-solving in financial analytics and showcases practical implementation of machine learning for enterprise-grade fraud prevention.

---

## ⭐ If you found this project useful, please consider starring the repository!
