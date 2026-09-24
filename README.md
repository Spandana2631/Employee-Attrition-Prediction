# Employee Attrition Prediction using Machine Learning

**IBM SkillsBuild | AICTE | BharatCares**  
**Data Analytics with AI Academic Internship 2026**

---

## Project Overview

This project builds an end-to-end **Employee Attrition Prediction** system using machine learning.  
The goal is to predict whether an employee is likely to leave the company and identify the key factors driving attrition.

**Dataset Source:**  
[Kaggle - IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

- Total Employees: **1,470**
- Attrition Rate: **~16%** (Yes)
- Features: Age, Department, Job Role, Monthly Income, OverTime, Job Satisfaction, Work-Life Balance, etc.
- Target: **Attrition** (Yes / No)

---

## Problem Statement

Employee attrition is costly for organizations (recruitment, training, lost productivity).  
This project helps HR teams identify employees at risk of leaving so that timely retention actions can be taken.

---

## Project Workflow

1. Data Loading & Exploration
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing (Encoding + Scaling + handling imbalance)
4. Model Building
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost Classifier
5. Model Evaluation & Comparison
6. Feature Importance & Business Insights

---

## Technologies Used

- **Python 3.x**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Machine Learning
- **Imbalanced-learn** – SMOTE
- **XGBoost** – Gradient boosting
- **Google Colab / Jupyter Notebook**

---

## How to Run the Project

### 1. Download the Dataset
1. Go to: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
2. Download `WA_Fn-UseC_-HR-Employee-Attrition.csv`
3. Rename it to `HR_Employee_Attrition.csv` (optional) and place it in the same folder

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
Open `Baskula_Spandana_Employee_Attrition_Colab.ipynb` in Google Colab and run all cells.

---

## Project Structure

```
Spandana_Employee_Attrition_Project/
├── Baskula_Spandana_Employee_Attrition_Colab.ipynb
├── Baskula_Spandana_Employee_Attrition.py
├── requirements.txt
├── README.md
└── Baskula_Spandana_ProjectReport.docx
```

---

## Author

**Baskula Spandana**  
IBM SkillsBuild Data Analytics with AI Internship  
BharatCares × AICTE × IBM  
September 2026

---

## License

This project is created for academic purposes as part of the IBM SkillsBuild Academic Internship.
