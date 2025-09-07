# ?? Employee Attrition Prediction System

Predicting whether an employee will leave the company using machine learning models trained on real-world HR data. This project is part of my Data Science portfolio and demonstrates end-to-end workflow including data cleaning, exploratory data analysis, feature engineering, model building, evaluation, and business interpretation.

---

## ?? Problem Statement

Employee attrition is a major concern for businesses globally. Retaining valuable employees is not only cost-effective but also critical to organizational success. Using the **IBM HR Analytics dataset**, this project aims to develop a predictive model that helps HR departments:

- Identify high-risk employees likely to leave
- Understand key factors contributing to attrition
- Take proactive retention strategies

---

## ?? Dataset Overview

- **Source**: [Kaggle - IBM HR Analytics Employee Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Rows**: 1,470 employees
- **Columns**: 35 features (e.g., Age, Gender, Department, JobSatisfaction, MonthlyIncome, etc.)
- **Target Variable**: `Attrition` (Yes/No)

---

## ?? Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Seaborn / Matplotlib | Data visualization |
| Scikit-learn | ML models, evaluation |
| Jupyter Notebook | Interactive coding |
| Git/GitHub | Version control and portfolio showcase |

---

## ?? Project Workflow

1. **Data Loading & Cleaning**
   - Handling missing values
   - Renaming columns
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Attrition rate by department, gender, and job role
   - Visual insights into satisfaction and income

3. **Feature Engineering**
   - Binning numerical variables
   - One-hot encoding
   - Feature selection

4. **Model Building**
   - Logistic Regression
   - Random Forest Classifier
   - Hyperparameter tuning

5. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - ROC AUC
   - Confusion Matrix

6. **Business Insights**
   - Top predictors of attrition
   - Strategic recommendations for HR

---

## ?? Key Results

- Best model: **Random Forest Classifier**
- Accuracy: ~88%
- Top 3 features: `JobSatisfaction`, `OverTime`, `MonthlyIncome`
- Insights:
  - Employees with low job satisfaction and high overtime are more likely to leave
  - Attrition is higher in certain departments

---



## ?? Results & Insights

- **Best Model:** Random Forest Classifier  
	Accuracy : 0.844
	Precision: 0.571
	Recall   : 0.085
	F1-Score : 0.148
	ROC-AUC  : 0.786  

### ?? Key Drivers of Attrition
- High overtime strongly correlates with attrition.
- Low job satisfaction and low monthly income increase risk.
- Departmental differences highlight retention challenges.

### ?? Business Recommendations
- Reduce overtime workload for high-risk groups.
- Improve engagement for dissatisfied employees.
- Review compensation strategies for low-salary roles.







## ?? What You’ll Learn (for Employers & Clients)

? Ability to conduct end-to-end data science workflow  
? Experience with HR analytics and classification problems  
? Strong command over feature engineering and model tuning  
? Ability to generate actionable business insights  

---

## ?? Dataset License

This dataset is publicly available for educational purposes and falls under the open data license by IBM (via Kaggle).

---

## ?? Contact

**Nafees Ayub**  
Data Scientist | Lecturer | Freelancer  
?? nafees.data@gmail.com  
?? [LinkedIn Profile](https://www.linkedin.com) (Update this link)  
?? Open to remote and international opportunities

---

