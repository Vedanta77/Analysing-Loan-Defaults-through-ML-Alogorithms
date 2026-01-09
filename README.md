# Analysing-Loan-Defaults-through-ML-Alogorithms
Machine learning–based credit risk analysis project for predicting loan defaults using Logistic Regression, Random Forest, and XGBoost after balancing the dataset with SMOTE.

## 📌 Project Description
This project focuses on **credit risk analysis** by predicting loan default behavior using machine learning models. The goal is to evaluate how different classifiers perform on financial data and to understand model behavior using appropriate evaluation metrics and visual analysis.

The project emphasizes correct handling of class imbalance, proper metric selection, and result interpretation rather than relying only on accuracy.

---

## 🎯 Objectives
- Clean and preprocess consumer credit data
- Balance the dataset using SMOTE
- Train and compare multiple machine learning models
- Evaluate model performance using numerical metrics and plots
- Analyze strengths and limitations of each model

---

## 📊 Dataset
Publicly available consumer credit datasets were used, containing:
- Borrower demographic details  
- Credit and loan information  
- Repayment history  
- Loan default status (target variable)

The problem is formulated as a **supervised binary classification task**.

---

## ⚙️ Methodology

### 1. Data Cleaning & Preprocessing
- Removed missing and inconsistent values  
- Dropped irrelevant identifiers  
- Encoded categorical variables  
- Prepared features for modeling  

### 2. Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**  
- Balanced the dataset to improve defaulter detection  

### 3. Models Implemented
- Logistic Regression  
- Random Forest  
- XGBoost  

### 4. Evaluation & Visualization
Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- AUC-ROC  

To support interpretation, the following **plots** were used:
- Confusion matrices  
- ROC curves  
- Performance comparison visualizations  

These plots helped analyze how each model behaves beyond numeric scores.

---

## 📈 Key Observations
- Logistic Regression was interpretable but had limited predictive strength.
- Random Forest achieved the most balanced and reliable performance.
- XGBoost showed high accuracy but failed to detect most defaulters.
- Visual analysis confirmed that accuracy alone is misleading for imbalanced data.

---

## 🧠 Conclusion
The project demonstrates that effective credit risk assessment requires careful preprocessing, balanced data, and multi-metric evaluation supported by visual analysis. Ensemble models can achieve strong performance, but model behavior must be examined using plots and class-wise metrics to ensure practical reliability.

---

## 🛠 Tools & Technologies
- Language: **Python**
- Environment: **Google Colab**
- Libraries: **Pandas, NumPy, Scikit-learn, XGBoost, imbalanced-learn**
- Visualization: **Matplotlib**

---

