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

3. **Data Preprocessing**  
   - Applied One-Hot Encoding for categorical variables  
   - Used StandardScaler for Logistic Regression  

4. **Handling Imbalanced Data**  
   - Applied SMOTE to improve minority class prediction (churn cases)  

5. **Model Building**  
   - Logistic Regression (baseline + optimized)  
   - Random Forest Classifier  

6. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC score for robust evaluation  

---

## 🤖 Models & Performance  

| Model                | Accuracy | ROC-AUC |
|---------------------|----------|--------|
| Logistic Regression | 80.5%    | 0.857  |
| Random Forest       | 80.2%    | 0.854  |

---

## 📊 Detailed Evaluation  

### 1:- Logistic Regression
- Accuracy: **80.48%**  
- ROC-AUC: **0.857**  

**Classification Report:**
- Recall (Churn): **0.94** 
- Precision (Churn): **0.82**  
- Recall (Non-Churn): **0.44** 

---

### 2:- Random Forest
- Accuracy: **80.27%**  
- ROC-AUC: **0.854**  

**Classification Report:**
- Recall (Churn): **0.93**   
- Precision (Churn): **0.83**  
- Recall (Non-Churn): **0.46**  

---

## 📈 Key Insights  

- Logistic Regression slightly outperformed Random Forest in ROC-AUC  
- Both models achieved **~80% accuracy with strong ROC-AUC (~0.85+)**  
- Models are highly effective at identifying **churn customers (high recall ~0.93–0.94)**  
- Lower recall for non-churn class indicates a bias toward predicting churn (acceptable in business scenarios)  

---

## 💡 Business Interpretation  

- The model prioritizes identifying churn customers, which is critical for retention strategies  
- Missing a churn customer is more costly than a false positive  
- This trade-off improves **customer retention targeting effectiveness**

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
