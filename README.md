# Chronic Kidney Disease Prediction using Machine Learning

##  Project Overview
This project aims to predict the presence of **Chronic Kidney Disease (CKD)** in patients using various **machine learning algorithms**. CKD is a critical condition that affects kidney function, and early detection can save lives. This project uses medical attributes to classify patients as **CKD positive** or **negative**.

---

##  Dataset
- **Source:** UCI Machine Learning Repository (Chronic Kidney Disease dataset)
- **Features:**  
  - `Age`, `Blood Pressure (Bp)`, `Specific Gravity (Sg)`, `Albumin (Al)`, `Sugar (Su)`, `Red Blood Cells (Rbc)`, `Blood Urea (Bu)`, `Serum Creatinine (Sc)`, `Sodium (Sod)`, `Potassium (Pot)`, `Hemoglobin (Hemo)`, `White Blood Cell Count (Wbcc)`, `Red Blood Cell Count (Rbcc)`, `Hypertension (Htn)`  
- **Target:**  
  - `ckd` → Patient has Chronic Kidney Disease  
  - `notckd` → Patient does not have Chronic Kidney Disease  

---

##  Technologies and Libraries
- Python
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`

---

##  Steps Performed
1. **Data Loading & Exploration**
   - Load dataset
   - Explore features and check data types

2. **Data Preprocessing**
   - Handle missing values
   - Convert categorical values into numerical
   - Feature scaling
   - Train-test split

3. **Model Building**
   - Implemented:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - XGBoost
     - KNN

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score
   - Confusion matrix for each model

5. **Model Comparison**
   - Compared accuracy of all models
   - Selected the best-performing model

---

##  Visualizations
- Correlation heatmap between features
- Distribution plots for important features
- Confusion matrices for model evaluation
- Accuracy comparison chart

---

##  Results
- **Random Forest** and **AdaBoost**  and **LogisticRegression** showed the best performance.

---

