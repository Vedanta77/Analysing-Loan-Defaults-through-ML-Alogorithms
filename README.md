# Analysing-Loan-Defaults-through-ML-Alogorithms
Machine learning–based credit risk analysis project for predicting loan defaults using Logistic Regression, Random Forest, and XGBoost after balancing the dataset with SMOTE.

## 📌 Project Overview
This project focuses on **credit risk analysis** by predicting loan default behavior using machine learning techniques. The objective is to evaluate and compare multiple classification models on imbalanced financial data and understand their effectiveness in identifying risky borrowers.

Loan default prediction is a critical task for financial institutions, as incorrect classification of defaulters can lead to significant financial losses. This project emphasizes proper evaluation metrics beyond accuracy to ensure reliable risk assessment.

---

## 🎯 Objectives
- Analyze and preprocess consumer credit data
- Handle class imbalance using SMOTE
- Train and evaluate multiple machine learning models
- Compare model performance using appropriate metrics
- Identify the most suitable model for credit risk prediction

---

## 📊 Dataset
The project uses **publicly available consumer credit datasets**, which include:
- Borrower demographic information  
- Credit history and loan details  
- Repayment behavior  
- Loan default status (target variable)

The target variable represents whether a borrower is a **defaulter or non-defaulter**, making this a supervised binary classification problem.

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Removed missing and invalid values
- Dropped irrelevant identifiers
- Encoded categorical variables
- Prepared features for model training

### 2. Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**  
- Balanced the dataset to improve defaulter detection

### 3. Machine Learning Models Used
- Logistic Regression  
- Random Forest  
- XGBoost  

### 4. Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- AUC-ROC  

Special emphasis was placed on **recall**, as missing defaulters poses higher financial risk.

---

## 📈 Key Findings
- **Logistic Regression** provided strong interpretability but limited predictive performance.
- **Random Forest** achieved the best overall results with high accuracy and balanced defaulter detection.
- **XGBoost** showed high accuracy but very low recall, missing many actual defaulters.
- Accuracy alone was found to be misleading for imbalanced credit risk datasets.

---

## 🧠 Conclusion
The project demonstrates that no single metric is sufficient for evaluating credit risk models. While ensemble models like Random Forest offer superior performance, careful metric selection is essential to avoid risky misclassifications. The study highlights the importance of recall and balanced evaluation in real-world financial decision-making.

---

## 🛠 Tools & Technologies
- Language: **Python**
- Environment: **Google Colab**
- Libraries: **Pandas, NumPy, Scikit-learn, XGBoost, imbalanced-learn**
- Visualization: **Matplotlib**

---

## 📂 Project Structure

