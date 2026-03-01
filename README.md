# TrustChain
Blockchain-Enabled Trust in Financial Analytics: Securing Large-Scale Distributed Transactions.
## Securing Large-Scale Distributed Transactions

## 📌 Project Overview

This project presents a hybrid architecture that integrates:

- Big Data Analytics
- Machine Learning-based Fraud Detection
- Blockchain-inspired Hash Validation

The objective is to secure large-scale financial transaction processing while ensuring data integrity and tamper resistance.

This implementation is based on the academic report:

"Blockchain-Enabled Trust in Financial Analytics: Securing Large-Scale Distributed Transactions"

---

## 🧠 Problem Statement

Traditional centralized financial systems are vulnerable to:

- Insider attacks
- Data tampering
- Integrity violations
- Single points of failure

This project addresses:

1. Intelligent fraud detection using ML
2. Tamper-evident validation using SHA-256 hash chaining

---

## 📂 Dataset

Credit Card Fraud Detection Dataset  
Source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

- 284,807 total transactions
- 492 fraudulent transactions
- Highly imbalanced dataset (0.172% fraud)
- PCA-transformed features (V1–V28)

---

## 🏗️ System Architecture

The system consists of:

1. Data Ingestion Layer
2. Distributed Storage Simulation
3. Analytics Processing Layer (ML Models)
4. Blockchain Validation Layer (SHA-256 hash anchoring)
5. Visualization & Reporting Layer

Note: Full blockchain infrastructure is simulated using cryptographic hashing rather than a public blockchain network.

---

## 📊 Machine Learning Models

- Logistic Regression
- Random Forest
- Gradient Boosting

Performance Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Achieved Fraud Detection Accuracy: **96.8%**

---

## 🔐 Blockchain Validation Simulation

- Transaction batches are hashed using SHA-256
- Hash values are chained sequentially
- Any modification changes the hash
- Tampering becomes immediately detectable

This ensures data immutability without storing full transactions on-chain.

---

## ⚙️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- hashlib (SHA-256)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

pip install -r requirements.txt

3. Download the dataset from Kaggle and place:

data/creditcard.csv

4. Run:

jupyter notebook

Open the notebook file to execute the pipeline.

---

## 🎓 Academic Context

Course: Big Data Analytics  
Department: Artificial Intelligence & Data Science  
Somaiya Vidyavihar University  
Academic Year: 2025–2026  

Contributors:
- Dhruv Shah
- Nimit Mehta
- Nikunj Mody
- Kevalya Rathod
