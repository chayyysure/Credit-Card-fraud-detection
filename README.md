# 💳 Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. It utilizes a real-world dataset to classify transactions as *Genuine* or *Fraudulent*, helping financial institutions minimize losses caused by fraud.

---

## 🧠 Overview

Credit card fraud detection is a major challenge due to the highly imbalanced nature of transaction data. This project focuses on building a predictive model capable of distinguishing between fraudulent and legitimate transactions through data analysis, visualization, and classification techniques.

The workflow includes:
- Data preprocessing and exploration  
- Handling class imbalance  
- Feature correlation analysis  
- Model training and evaluation  

---

## 📊 Dataset

The dataset used is the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).  
It contains **284,807 transactions** with **492 frauds (0.172%)** recorded over two days in September 2013.

| Column | Description |
|---------|-------------|
| `Time` | Seconds elapsed between each transaction and the first transaction |
| `V1` – `V28` | Principal components obtained from PCA |
| `Amount` | Transaction amount |
| `Class` | Target variable — 0 for Genuine, 1 for Fraud |

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit_card_fraud_detection.git
   cd credit_card_fraud_detection
