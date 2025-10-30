# 🚀 Intrusion Detection System for IoT Devices using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/AI%2FML-XGBoost-brightgreen)
![IoT Security](https://img.shields.io/badge/IoT-Security-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

  
This project implements a Machine Learning-based Intrusion Detection System (IDS) for IoT environments.  
It uses the XGBoost algorithm to detect various types of cyber-attacks with high accuracy.

---

## Features

- Automated data preprocessing  
- Class balancing using RandomOverSampler  
- High accuracy XGBoost model  
- Model saving and loading with joblib  
- Performance evaluation and visualization  

---

## Dataset Overview

| Attribute | Details |
|------------|----------|
| **Records** | 1,048,575 samples |
| **Features** | 21 (20 input + 1 target) |
| **Classes** | 34 (attack + benign) |
| **Target Column** | label |
| **Accuracy** | 99.33% |

---

## Model Performance

| Metric | Score |
|---------|--------|
| **Accuracy** | 0.9933 |
| **Precision (avg)** | 0.99 |
| **Recall (avg)** | 0.99 |
| **F1-Score (macro)** | 0.81 |

---

## Repository Structure

| File Name | Description |
|------------|-------------|
| `IDS_Training.ipynb` | Main Jupyter notebook containing the full ML pipeline |
| `xgb_ids_20250921.pkl` | Trained XGBoost model |
| `label_encoder_20250921.pkl` | Label encoder for target labels |
| `feature_encoders_20250921.pkl` | Encoders for categorical features |
| `features_20250921.json` | List of features used for training |
| `README.md` | Project documentation (you are here) |

---

## Tech Stack

- Python 3  
- pandas  
- numpy  
- scikit-learn  
- imbalanced-learn  
- xgboost  
- matplotlib  
- seaborn  

---

## 🤝 Let's Connect
 ### 🖊️Author: Muhammad Anique 
📧 **Email:** aniquee.ai@gmail.com  
🌍 **GitHub:** [github.com/Sigmaog](https://github.com/Sigmaog)

---
