# Employee Attrition Prediction

## Problem Statement

Employee attrition, the phenomenon of employees voluntarily or involuntarily leaving an organization, is a critical challenge for businesses. High attrition rates can lead to:

- **Increased operational costs** (e.g., recruitment, training, and lost productivity).
- **Disruption in team dynamics** and project continuity.
- **Loss of institutional knowledge** and expertise.

### The Challenge
Organizations often struggle to identify employees at risk of leaving until it’s too late. Traditional methods of attrition analysis are reactive and fail to address root causes such as:
- Job dissatisfaction
- Lack of career growth
- Poor work-life balance
- Inadequate compensation
- Managerial issues

### Objective
This project aims to **predict employee attrition proactively** using machine learning. By analyzing historical employee data, the model identifies patterns and risk factors associated with attrition, enabling organizations to:
- **Intervene early** with retention strategies (e.g., promotions, salary adjustments, or mentorship programs).
- **Reduce turnover costs** and maintain workforce stability.
- **Improve employee satisfaction** by addressing systemic issues.

---

## Dataset
The dataset (`HR-Employee-Attrition.csv`) includes **35 features** for **1,470 employees**, such as:
- **Demographics**: Age, Gender, Marital Status
- **Job-related**: Department, Job Role, Monthly Income, Years at Company
- **Behavioral**: Job Satisfaction, Work-Life Balance, Overtime, Training Frequency

**Target Variable**: `Attrition` (binary: `Yes`/`No` indicating whether the employee left).

---

## Approach
1. **Exploratory Data Analysis (EDA)**: Visualize trends and correlations between features and attrition.
2. **Data Preprocessing**: Handle categorical variables (one-hot encoding) and scale numerical features.
3. **Model Development**: Train and evaluate multiple classification algorithms (e.g., Logistic Regression, Random Forest, AdaBoost).
4. **Insights**: Identify key drivers of attrition and recommend actionable strategies.

---

## Key Results
- The **AdaBoost Classifier** achieved the highest accuracy (88%) in predicting attrition.
