# Employee Attrition Prediction Using Machine Learning

## Project Overview

Employee attrition is one of the biggest challenges faced by organizations, as high employee turnover increases recruitment costs, training expenses, and reduces overall productivity. This project aims to analyze employee data and build machine learning models that can predict whether an employee is likely to leave the organization. The project also identifies the key factors contributing to employee attrition and provides actionable business recommendations to improve employee retention.


## Internship Project Information

**Project Title:** Employee Attrition Prediction Using Machine Learning

**Domain:** Human Resources Analytics (HR Analytics)

**Project Type:** Data Science Internship Project

## Objectives

* Analyze employee data to understand factors affecting attrition.
* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA) using visualizations.
* Build and compare multiple machine learning models.
* Evaluate model performance using standard classification metrics.
* Identify the most important features influencing employee attrition.
* Provide business insights and HR recommendations.


## Dataset Information

* **Dataset:** IBM HR Analytics Employee Attrition Dataset
* **Total Employees:** 1470
* **Total Features:** 35
* **Target Variable:** Attrition (Yes / No)


## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Machine Learning Models

The following classification models were implemented and evaluated:

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier


## Model Performance

| Model                 | Accuracy   |
| --------------------- | ---------- |
| Logistic Regression   | **75.17%** |
| Random Forest         | **83.67%** |
| **Gradient Boosting** | **85.03%** |

**Best Performing Model:** Gradient Boosting

**ROC-AUC Score:** 0.794


## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Cleaning and Preprocessing
4. Missing Value Analysis
5. Exploratory Data Analysis (EDA)
6. Feature Encoding
7. Train-Test Split
8. Feature Scaling
9. Machine Learning Model Training
10. Model Evaluation
11. Feature Importance Analysis
12. Business Insights
13. HR Recommendations


## Exploratory Data Analysis

The following visualizations were created during the analysis:

* Attrition by Department
* Attrition by Job Role
* Monthly Income vs Attrition
* Work-Life Balance vs Attrition
* Years at Company vs Attrition
* Confusion Matrix
* Feature Importance

## Key Findings

* Monthly Income was one of the strongest predictors of employee attrition.
* Employees who worked overtime were more likely to leave the organization.
* Employee age and total working experience significantly influenced attrition.
* Employees in the early years of their careers showed higher attrition rates.
* Workplace satisfaction and job involvement also contributed to employee retention.


## Business Recommendations

* Reduce excessive overtime to improve work-life balance.
* Review salary structures for employees with lower income levels.
* Strengthen employee engagement and satisfaction initiatives.
* Implement mentorship and career development programs for new employees.
* Conduct regular employee feedback surveys to improve retention.


## Project Structure

employee-attrition-prediction/
│
├── analysis.ipynb
├── README.md
├── requirements.txt
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── HR_Director_Executive_Summary.docx
│
└── charts/
    ├── department_attrition.png
    ├── jobrole_attrition.png
    ├── income_attrition.png
    ├── worklifebalance_attrition.png
    ├── years_company_attrition.png
    ├── confusion_matrix.png
    └── feature_importance.png


## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/employee-attrition-prediction.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:
```text
analysis.ipynb
```

Run all cells sequentially.

## Future Improvements

* Improve prediction performance for employee attrition cases.
* Address class imbalance using advanced resampling techniques.
* Experiment with additional machine learning algorithms.
* Develop an interactive HR dashboard for real-time attrition monitoring.


## Author

**Tirth Patel**

B.Tech – Artificial Intelligence & Data Science

Sankalchand Patel University

GitHub: https://github.com/tirth-datamaster

This project was developed for educational and internship learning purposes.
