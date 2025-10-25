# 🚀 Intrusion Detection System for IoT Devices using Machine Learning

## 🧠 Overview
This project implements an **Intrusion Detection System (IDS)** for IoT networks using **Machine Learning** — specifically **XGBoost** with **SMOTE balancing**.  
The system can detect multiple network attack types (e.g., **PortScan**, **BruteForce**, **DDoS**, etc.) and classify them efficiently even with **imbalanced data**.

---

## 🧩 Key Features
- ✅ Handles **imbalanced datasets** using SMOTE  
- ✅ Automatically merges **rare classes** into "Other"  
- ✅ Uses **XGBoost (multi-class classification)**  
- ✅ Generates accuracy, classification report & confusion matrix  
- ✅ Saves trained **model**, **encoders**, and **feature metadata** for reuse  
- ✅ Clean and reproducible ML pipeline  

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install pandas scikit-learn xgboost imbalanced-learn joblib matplotlib seaborn numpy
