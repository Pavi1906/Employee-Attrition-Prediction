# Employee Attrition Prediction using Machine Learning

## Project Overview

Employee attrition is a major challenge for organizations because losing skilled employees increases recruitment costs and reduces productivity. This project develops a Machine Learning model that predicts whether an employee is likely to leave the company based on HR analytics data.

The project performs complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and business recommendations for HR departments.

---

## Objectives

- Analyze employee attrition patterns.
- Perform Exploratory Data Analysis (EDA).
- Build multiple machine learning classification models.
- Compare model performance.
- Identify the most important factors affecting attrition.
- Provide HR insights and business recommendations.

---

## Dataset

IBM HR Analytics Employee Attrition Dataset

Dataset File:

```
WA_Fn-UseC_-HR-Employee-Attrition.csv
```

Target Variable:

- Attrition
  - Yes (Employee Left)
  - No (Employee Stayed)

---

## Project Structure

```
EmployeeAttrition_Pavithra/
│
├── analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── dataset_audit_report.csv
├── summary.docx
├── requirements.txt
├── README.md
└── charts/
```

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Workflow

### Data Preprocessing

- Missing value checking
- Duplicate checking
- Feature encoding
- Feature scaling
- Train-Test Split

### Exploratory Data Analysis

- Department-wise Attrition
- Job Role Analysis
- Monthly Income Analysis
- Age Distribution
- Overtime Analysis
- Correlation Heatmap

### Machine Learning Models

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

---

## Model Performance

| Model | Accuracy | Precision | Recall | ROC-AUC |
|-------|----------|-----------|--------|---------|
| Logistic Regression | 75.17% | 34.52% | 61.70% | 79.83% |
| Random Forest | **83.67%** | 44.44% | 8.51% | 77.04% |
| Gradient Boosting | 85.03% | 58.82% | 21.28% | 79.41% |

---

## Key Findings

- Monthly Income strongly influences employee attrition.
- Employees working overtime have higher attrition.
- Years at Company impacts retention.
- Age influences resignation probability.
- Distance from Home also contributes to employee turnover.

---

## Business Recommendations

- Improve work-life balance.
- Monitor employee overtime.
- Review salary structures.
- Conduct employee engagement surveys.
- Develop targeted employee retention strategies.

---

## Project Limitations

- Dataset contains historical HR data only.
- External economic factors were not included.
- Human behaviour changes over time.
- Models require periodic retraining.

---

## Future Improvements

- Hyperparameter tuning.
- Cross-validation.
- Deployment using Streamlit or Flask.
- Real-time prediction API.
- Cloud deployment.

---

## Results

The project successfully compared three classification algorithms for predicting employee attrition.

- Random Forest achieved the highest accuracy.
- Logistic Regression achieved the highest recall.
- Gradient Boosting provided balanced performance.

This project demonstrates how Machine Learning can support HR departments in proactive employee retention.

---

## Author

**Pavithra P**

MCA Student

GitHub: https://github.com/Pavi1906

LinkedIn: https://www.linkedin.com/in/pavithra-p-86ab722a4/

---
