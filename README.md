# # Bank Term Deposit Prediction - Machine Learning Model Comparison

## 📌 Project Overview
This project analyzes the **Bank Marketing dataset** from UCI to predict whether a client will subscribe to a term deposit. The dataset is highly imbalanced (88% "No", 12% "Yes").

## 🎯 Goal
Build and compare multiple machine learning models to identify potential term deposit customers.

## 📊 Dataset
- **Source:** UCI Machine Learning Repository - Bank Marketing Dataset
- **Samples:** 6,590 contacts
- **Features:** Age, job, marital status, education, balance, housing loan, contact method, etc.
- **Target:** Term deposit subscription (Yes/No)

## 🤖 Models Evaluated
| Model | Recall (Yes) | Precision (Yes) | F1-Score |
|-------|--------------|-----------------|----------|
| KNN | 24.4% | 50.1% | 0.328 |
| Neural Network | 20.7% | 56.4% | 0.302 |
| SVM (RBF) | 19.1% | 57.9% | 0.287 |
| Decision Tree | 17.7% | 54.1% | 0.266 |
| Logistic Regression | 15.5% | 58.3% | 0.245 |

## 🏆 Best Model
**KNN achieved the highest F1-Score (0.328) and Recall (24.4%)** for detecting the minority class.

## 🛠️ Technologies Used
- Python 3.x
- scikit-learn
- pandas, numpy
- matplotlib, seaborn

## 📁 Files
- `bank_term_deposit_ml_analysis.ipynb` - Main Jupyter notebook with all models
- `Bank-Term-Deposit-Dataset.xlsx` - Dataset file

## 🔍 Key Findings
- The dataset has severe class imbalance (88% negative class)
- KNN outperformed other models for minority class detection
- Further improvement possible with SMOTE or RUSBoost techniques


## 📚 Future Work
- Apply SMOTE oversampling
- Test XGBoost with scale_pos_weight
- Hyperparameter tuning

## 📧 Parisa Mohammadi
https://github.com/ParisaMohammadi9094

---
⭐ Star this repo if you find it useful!
