# 🏦 Credit Scoring Model
### CodeAlpha Machine Learning Internship — Task 1

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

---

## 📌 Objective
Predict whether a person is **creditworthy (good/bad risk)** 
using financial and demographic data from the German Credit Dataset.

---

## 📊 Dataset
| Property | Details |
|---|---|
| Name | German Credit Data |
| Samples | 1000 |
| Features | 10 |
| Target | Risk (good / bad) |
| Class Distribution | 700 Good, 300 Bad |

---

## 🔍 Project Workflow
1. Data Loading & Exploration
2. Handling Missing Values
3. Exploratory Data Analysis (EDA)
4. Label Encoding & Feature Scaling
5. Outlier Removal (IQR Method)
6. Model Training & Comparison
7. Evaluation — Accuracy, ROC-AUC, Confusion Matrix
8. Feature Importance Analysis

---

## 🤖 Models Used
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | ~56% | ~0.66 |
| Decision Tree | ~61% | ~0.59 |
| **Random Forest** ✅ | **~75%** | **~0.74** |

---

## 📈 Key Results
- ✅ Best Model — Random Forest Classifier
- ✅ class_weight='balanced' used to handle class imbalance
- ✅ 5-Fold Cross Validation applied
- ✅ Top features — Duration, Credit Amount, Age

---

## 🛠️ Libraries Used
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 👩‍💻 Author
**Sakshi Chougule**
B.Tech CSE (AI & ML) — Rajarambapu Institute of Technology
CodeAlpha ML Internship 2026
