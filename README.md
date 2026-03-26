# 📊 Telco Customer Churn Prediction

## 🔍 Problem Statement
Customer churn is a critical business challenge where companies lose existing customers, leading to revenue loss. This project aims to **predict customer churn** and enable businesses to take proactive retention actions.

---

## 🎯 Business Objective
- Identify customers with high churn risk  
- Improve retention strategies  
- Minimize revenue loss through early intervention  

---

## 📁 Dataset
The dataset includes:
- Customer demographics  
- Subscription details  
- Billing & payment information  
- Service usage patterns  

---

## ⚙️ Workflow

1. **Data Cleaning**  
   - Handled missing values using median  
   - Converted data types for consistency  

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed churn distribution  
   - Identified key drivers such as Monthly Charges and Contract type  

3. **Feature Engineering**  
   - Created derived features to improve model performance  

4. **Data Preprocessing**  
   - Applied One-Hot Encoding for categorical variables  
   - Used StandardScaler for Logistic Regression  

5. **Handling Imbalanced Data**  
   - Applied SMOTE to improve minority class prediction (churn cases)  

6. **Model Building**  
   - Logistic Regression (baseline + optimized)  
   - Random Forest Classifier  

7. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC score for robust evaluation  

---

## 🤖 Models Used

### 🔹 Logistic Regression
- Accuracy: **81.6%**  
- ROC-AUC: **0.86**  
- Strong recall for identifying churn customers  

### 🔹 Random Forest
- Accuracy: **80.2%**  
- ROC-AUC: **0.85**  

---

## 📊 Key Results

- Achieved **ROC-AUC of 0.86**, indicating strong predictive performance  
- Logistic Regression outperformed Random Forest  
- Improved detection of churn customers using SMOTE  
- Achieved a good balance between precision and recall  

---

## 💡 Business Impact

- Enables early identification of high-risk customers  
- Supports targeted retention strategies  
- Helps reduce customer acquisition costs  
- Drives data-driven decision making for business teams  

---

## 🧠 Conclusion

This project demonstrates an end-to-end machine learning pipeline for churn prediction, combining data preprocessing, imbalance handling, and model evaluation to solve a real-world business problem effectively.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn, Matplotlib  
- Imbalanced-learn (SMOTE)  

---

## 📌 Author
Aniket Yadav
