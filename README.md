# 🚀 Intrusion Detection System for IoT Devices using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/AI%2FML-XGBoost-brightgreen)
![IoT Security](https://img.shields.io/badge/IoT-Security-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📘 Overview  

This repository contains a **Machine Learning-based Intrusion Detection System (IDS)** designed for **IoT networks**.  
The system identifies malicious or abnormal activities in IoT traffic data using advanced ML models such as **XGBoost**.  

It aims to strengthen IoT device security by automatically learning attack patterns from network datasets and detecting potential threats efficiently.  

---

## 🧠 Key Features  

✅ Data Preprocessing & Feature Encoding  
✅ Balanced Training using **SMOTE / RandomOverSampler**  
✅ Multi-class Classification (Normal, PortScan, BruteForce, etc.)  
✅ Model Training & Evaluation using **XGBoost**  
✅ Visual Results – Confusion Matrix & Feature Importance  
✅ Saved Model Artifacts for Deployment  

---

## 📂 Repository Structure  

| File Name | Description |
|------------|-------------|
| `Intrusion IDS.ipynb` | Main Jupyter notebook containing the full ML pipeline |
| `xgb_ids_20250921.pkl` | Trained XGBoost model |
| `label_encoder_20250921.pkl` | Label encoder for target labels |
| `feature_encoders_20250921.pkl` | Encoders for categorical features |
| `features_20250921.json` | List of features used for training |
| `README.md` | Project documentation (you are here) |

---

## ⚙️ Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Sigmaog/Intrusion-Detection-System-IoT.git
cd Intrusion-Detection-System-IoT
---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install pandas scikit-learn xgboost imbalanced-learn joblib matplotlib seaborn numpy
