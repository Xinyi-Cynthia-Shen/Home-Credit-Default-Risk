# 🏦 MMF2030 Machine Learning for Finance: Home Credit Default Risk Project

## 📚 Overview

This repository contains the full project for the **Home Credit Default Risk** case study, completed for the **MMF2030 Machine Learning for Finance** course at the University of Toronto. The goal of this project is to predict the likelihood of a client defaulting on a loan using advanced machine learning techniques.

The project explores various stages of the data science pipeline—from data preprocessing and feature engineering to model building and business analysis—with a strong focus on practical applications in credit risk management.


## 💡 Project Objective

The objective is to develop a predictive model that classifies clients into **default** or **non-default** categories using historical and transactional data. This classification improves loan approval decisions and helps mitigate credit risk for financial institutions.

**Challenges Addressed:**  
- Reducing false positives and false negatives in credit decisions.  
- Enhancing financial inclusion for low-risk applicants.  
- Balancing risk management with profitability.


## 🔍 Project Components

### 1. **Group Component**  
**File:** `MMF2030_Project_Group_Component.pdf`  
**Authors:** Shuqi (Serena) Chang, Ruoxu (Ryan) Jiang, Xinyi (Cynthia) Shen, Surui (Alex) Zhang  

**Highlights:**  
- **Data Cleaning & Preprocessing**: Handled missing values, scaling, and encoding.  
- **Feature Engineering**: Created new variables from transactional and credit data.  
- **Modeling**: Implemented **XGBoost** and **Random Forest** with hyperparameter tuning.  
- **Evaluation**: Used **ROC-AUC**, **F1-Score**, and **Profit Curve Analysis** for performance metrics.


### 2. **Individual Component**  
**File:** `MMF2030_Project_Individual_Component_Xinyi_Cynthia_Shen.pdf`  
**Author:** Xinyi (Cynthia) Shen  

**Note:** This report was originally based on **Alex's code**, but Cynthia's version (`MMF2030_Project_Code_Cynthia.ipynb`) is cleaner, more efficient, and eliminates excessive warnings. While some numerical outputs differ slightly, Cynthia's code produces more stable results.

**Highlights:**  
- **Business Insights**: Profit optimization through threshold adjustment.  
- **Profit Curve Analysis**: Maximum profit of **$35,513** at a threshold of **0.16**.  
- **Model Evaluation**:  
  - **ROC AUC:** 0.75  
  - **Accuracy:** 86%  
  - **Precision (Non-default):** 94%  
  - **Recall (Default):** 39%  

### 3. **Code Implementations**  
**Recommended:** `MMF2030_Project_Code_Cynthia.ipynb`  
- **Clean Code:** Organized and well-documented Python code with minimal warnings.  
- **Optimized Workflow:** Streamlined data preprocessing, feature engineering, and model evaluation.  
- **Reproducibility:** Clear structure for replicating results and running model evaluations.
- **Output:** Since we wrote the report based on the other version of code run by Alex, the outputnumbers are slightly different from the individual-written report.

**Reference:** `MMF2030_Project_Code_Alex.ipynb`  
- Used as the foundation for the individual report but contains more verbose outputs and warnings.

**Key Techniques:**  
- **XGBoost** and **Random Forest** classifiers.  
- **Hyperparameter Tuning** with GridSearchCV.  
- **Profit Curve Analysis** for business-aligned decision thresholds.

## 🏆 Results

- **Best Model:** XGBoost (Optimized for ROC AUC)  
- **ROC AUC:** 0.75  
- **Accuracy:** 86%  
- **Maximum Profit:** $35,513  
- **Optimal Threshold:** 0.16  

**Business Impact:**  
- Improved credit risk management and proactive risk mitigation.  
- Enhanced financial inclusion for low-risk borrowers.  
- Increased operational efficiency via automated decision-making.

## ⚙️ Tools & Technologies

- **Python**  
- **Jupyter Notebook**  
- **XGBoost**, **Random Forest**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **GridSearchCV** for hyperparameter tuning  
- **ROC-AUC**, **F1-Score**, **Profit Curve Analysis**

## 📈 Business Applications

1. **Credit Risk Assessment:** Real-time credit scoring for loan approvals.  
2. **Risk-Based Pricing:** Adjust loan interest rates based on risk classifications.  
3. **Fraud Detection:** Identify suspicious applications through anomaly detection.  
4. **Portfolio Monitoring:** Dynamic adjustment of lending strategies in response to economic changes.

## 🎓 Acknowledgments

- **University of Toronto – Master of Mathematical Finance Program**  
- **MMF2030 Machine Learning for Finance Course**

---

Let me know if you'd like further adjustments or improvements!
