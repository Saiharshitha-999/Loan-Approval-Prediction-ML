# 🚀 Loan Approval Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting whether a loan will be approved or not based on applicant details using supervised machine learning techniques.  
It includes data preprocessing, handling imbalanced data, model comparison, and hyperparameter tuning.

---

## 📊 Dataset Features
The dataset includes:
- Applicant Income  
- Coapplicant Income  
- Loan Amount  
- Loan Term  
- Credit History  
- Gender, Married Status, Education  
- Property Area and more  

---

## 🔍 Data Preprocessing
- Handled missing values using mean/mode imputation  
- Converted categorical variables using One-Hot Encoding  
- Processed special cases like **"3+" dependents**  
- Removed irrelevant column **Loan_ID**  

---

## ⚖️ Handling Imbalanced Data
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**  
- Balanced the dataset to improve model performance  

---

## 🤖 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  

---

## ⚙️ Hyperparameter Tuning
Used **GridSearchCV** to optimize:
- Logistic Regression → Regularization (C), solver  
- Decision Tree → max_depth, min_samples_split  
- Random Forest → n_estimators, max_depth  
- KNN → n_neighbors, weights  

---

## 📈 Model Performance (Before Tuning)

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 78.8%    |
| Random Forest       | 77.2%    |
| KNN                 | 74.7%    |
| Decision Tree       | 73.9%    |

---

## 📊 Key Observations
- Logistic Regression performed consistently with strong recall  
- Random Forest handled complex patterns effectively  
- Decision Tree improved after tuning by reducing overfitting  
- KNN showed limited improvement, highlighting its dependency on feature scaling  

---

## 💡 Key Learnings
- Data preprocessing plays a crucial role in ML performance  
- Handling imbalanced data improves model fairness  
- Different models respond differently to hyperparameter tuning  
- Feature scaling is important for distance-based models like KNN  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 🚀 Future Improvements
- Apply feature scaling to improve KNN performance  
- Deploy using Streamlit for real-time predictions  
- Experiment with advanced ensemble techniques  

---

## 📌 Conclusion
This project demonstrates a complete machine learning workflow — from data cleaning to model optimization and evaluation.

---
