# 🧠 Customer Churn Prediction using Machine Learning  

## 📊 Overview  
This project predicts *customer churn* — identifying customers likely to discontinue a service. Using a Kaggle dataset, multiple machine learning models were trained and compared to find the most accurate churn prediction approach.

---

## 📁 Dataset Information  
*Source:* [Kaggle - Customer Churn Dataset](https://www.kaggle.com/)  


*Description:*  
The dataset includes customer demographics, account details, and usage metrics.  
The target variable Churn indicates whether a customer has left the company (1) or stayed (0).  

*Key Features:*  
- gender – Male/Female  
- SeniorCitizen – Whether the customer is a senior citizen  
- Partner, Dependents – Family details  
- tenure – Number of months the customer has stayed  
- PhoneService, InternetService, Contract, PaymentMethod  
- MonthlyCharges, TotalCharges  
- Churn – Target variable (Yes/No)  

---

## 🎯 Objective  
To build a machine learning model that accurately predicts *customer churn* using historical behavior and service usage patterns.

---

## 🧩 Project Workflow  

### 1️⃣ Data Collection  
- Dataset downloaded from Kaggle  
- Imported and analyzed using *Pandas*

### 2️⃣ Data Preprocessing  
- Missing value treatment  
- Encoding categorical variables  
- Normalization using *StandardScaler*  
- Train-test split (80%-20%)

### 3️⃣ Exploratory Data Analysis (EDA)  
- Visualized churn rate and correlations  
- Analyzed demographics and contracts  
- Used *Matplotlib* and *Seaborn* for insights  

### 4️⃣ Model Development  
Trained and evaluated models:  
- Logistic Regression  
- Random Forest Classifier  
- XGBoost  
- Support Vector Machine (SVM)  
- Neural Network (optional)

### 5️⃣ Model Evaluation  
Metrics used:  
- Accuracy  
- Precision, Recall, F1-score  
- ROC-AUC  
- Confusion Matrix  

---

## 🏆 Results  

| Model | Accuracy | Precision | Recall | F1-Score | AUC |
|--------|-----------|-----------|---------|-----------|------|
| Logistic Regression | 0.80 | 0.78 | 0.76 | 0.77 | 0.83 |
| Random Forest | 0.86 | 0.84 | 0.83 | 0.83 | 0.90 |
| XGBoost | *0.88* | *0.86* | *0.85* | *0.85* | *0.92* |
| SVM | 0.82 | 0.80 | 0.79 | 0.79 | 0.85 |

✅ *Best Model:* XGBoost (Highest Accuracy and AUC)

---

## 🧠 Model Explainability  
Used *SHAP* and *Feature Importance* plots for interpretation.  
*Top churn drivers:*  
- Contract type (month-to-month)  
- High monthly charges  
- Short tenure  
- Lack of online security or tech support  

---

## 🧰 Tech Stack  

*Languages:*  
- Python  

*Libraries:*  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  
- SHAP  

*Tools:*  
- Jupyter Notebook / Google Colab  
- Kaggle  
- GitHub  

---

## 🧩 Folder Structure
