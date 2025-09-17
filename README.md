# 🩺 Diabetes Risk Predictor

## 📌 Overview
Diabetes is a chronic illness affecting millions globally, with rising prevalence in Kenya and other developing regions.  
Early detection is essential for preventing complications and reducing long-term healthcare costs.  

This project develops a **machine learning model** to classify individuals as diabetic or non-diabetic using **demographic, lifestyle, and clinical features**.  
The dataset (sourced from Kaggle) includes variables such as:
- Age  
- Gender  
- BMI  
- Blood Glucose Level  
- Hypertension Status  
- Smoking History  
- HbA1c Levels  

By applying **data preprocessing, feature engineering, and model optimization**, the project aims to support proactive screening and decision-making in clinical settings.

---

## ⚙️ Project Workflow
1. **Data Collection & Exploration**  
   - Load dataset and explore variables  
   - Check for missing values and class distribution  

2. **Data Preprocessing**  
   - Clean unrealistic values  
   - Encode categorical features  
   - Scale numerical variables  

3. **Exploratory Data Analysis (EDA)**  
   - Visualize age distribution, diabetes by gender, etc.  

4. **Feature Engineering**  
   - Create interaction terms (e.g., Age × BMI)  

5. **Model Training & Evaluation**  
   - Logistic Regression  
   - Random Forest  
   - SMOTE for class imbalance handling  

6. **Hyperparameter Tuning**  
   - GridSearchCV for best parameters  
   - Model comparison using ROC-AUC  

---

## 📊 Results
- **Logistic Regression (Optimized):** ROC-AUC = **0.962**  
- **Random Forest (Optimized):** ROC-AUC = **0.967**  

👉 Random Forest showed the best overall performance with high accuracy and balanced recall.

---

## ✅ Final Recommendation
The **Random Forest model** is recommended for deployment due to its robustness, ability to handle feature interactions, and superior ROC-AUC performance.  
It can be integrated into healthcare screening systems to **identify high-risk individuals early**.

---

## 📘 Learnings
- Handling **imbalanced datasets** using SMOTE improved model fairness.  
- Feature scaling and encoding were critical for better accuracy.  
- Model tuning (GridSearchCV) significantly boosted predictive power.  
- Visualizations helped uncover key patterns (e.g., higher diabetes risk with age and BMI).  

---

## 🙌 Acknowledgements
- Dataset: Kaggle Diabetes Prediction Dataset
- Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn
- Inspiration: Supporting public health through AI-driven solutions

## 👩‍💻 Author
**Nancy Kamau**
