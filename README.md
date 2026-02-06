# 📉 Employee Attrition Prediction  
### 🤖 Predictive Analytics & Machine Learning in HR

> A data-driven project using exploratory data analysis and machine learning models to identify the key factors influencing employee attrition and predict which employees are at risk of leaving.

---

## 📌 Project Overview

Employee attrition creates significant costs for organizations, including lost productivity, rehiring expenses, and decreased morale.  
This project analyzes HR employee data to uncover **why employees leave** and to **predict attrition risk** using machine learning models.

### 🎯 Project Objectives
- Identify the key drivers of employee attrition  
- Build predictive models to classify employees as likely to stay or leave  
- Provide actionable, data-backed recommendations to reduce turnover  

---

## 🗂 Dataset Description

**Dataset:** HR Employee Attrition Dataset  

The dataset includes employee-level attributes such as:
- Age  
- Job Level  
- Monthly Income  
- Job Satisfaction  
- Performance Rating  
- Overtime Status  
- Years at Company  
- Years with Current Manager  
- Attrition (Target Variable)

---

## 🛠 Tools & Technologies

- 🐍 **Python**
  - Pandas
  - NumPy
  - Matplotlib / Seaborn
  - Scikit-learn
- 📊 Exploratory Data Analysis (EDA)
- 🤖 Machine Learning
  - Logistic Regression
  - Random Forest Classifier

---

## 🧹 Data Preparation

To prepare the data for analysis and modeling:

- Converted categorical variables into numerical format using binarization/encoding  
- Analyzed variable relationships using correlation matrices and heatmaps  
- Removed low-impact and highly correlated variables to reduce noise  
- Evaluated multicollinearity to improve model stability  

---

## 📊 Exploratory Data Analysis

### 🔍 Key Correlations & Insights

- **Overtime** showed a positive relationship with attrition  
- **Age** was slightly negatively correlated with attrition, indicating older employees were marginally less likely to leave  
- **Years with Current Manager** had a negative relationship with attrition, suggesting management stability improves retention  
- **Monthly Income** and **Job Level** were negatively correlated with attrition  
- Career progression variables (Years at Company, Years in Role, Years Since Last Promotion) were strongly correlated with one another  

These relationships highlight the importance of **career growth, compensation, and workload balance** in employee retention.

---

## 🤖 Predictive Modeling

Two complementary models were developed:

### 1️⃣ Logistic Regression
- Selected due to the binary nature of attrition (Yes/No)
- Provides interpretability for understanding feature impact

⚠️ **Model Adjustment:**  
The *Performance Rating* variable caused overfitting due to an extremely strong correlation with attrition. It was removed to improve model generalization and reduce bias.

---

### 2️⃣ Random Forest Classifier
- Handles nonlinear relationships and feature interactions  
- Robust against noise and complex workforce patterns  

Random Forest helped uncover deeper patterns across satisfaction, tenure, compensation, and overtime variables.

---

## 💡 Key Findings

- Employees with **lower income, lower job level, and shorter tenure** were more likely to leave  
- **Overtime** increased attrition risk  
- Longer relationships with the same manager reduced attrition likelihood  
- Career stability and progression strongly influence employee retention  

Both models demonstrated that employee attrition can be predicted with meaningful accuracy using HR data.

---

## 🚀 Business Recommendations

Organizations can reduce turnover by:

- Monitoring employees with **high overtime and low tenure**  
- Strengthening **career development and promotion pathways**  
- Supporting consistent **manager–employee relationships**  
- Reviewing compensation structures for at-risk employee groups  
- Using predictive models to proactively identify and support high-risk employees  

---

## 📈 Business Impact

This project demonstrates how predictive analytics can help HR teams:

✔ Move from reactive to proactive retention strategies  
✔ Identify attrition risk early  
✔ Support data-driven workforce planning  

---

## 🏁 Conclusion

By combining exploratory data analysis with machine learning models, this project shows how employee data can be transformed into actionable insights that directly support organizational decision-making.

It highlights skills in:
- Data cleaning and EDA  
- Predictive modeling  
- Business-focused insight generation  

---

📬 *Explore more of my projects here.*
