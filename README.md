Here's the updated README incorporating the new details on Tableau storytelling:

---

# Home Loan Approval Data Visualization Project 

This project showcases my proficiency in **Excel**, **SAS Viya**, and **Tableau** through data analysis, visualization, and storytelling, focusing on home loan approval patterns. The goal is to provide actionable insights into the loan approval process while demonstrating proficiency in the data visualization domain.

[**Project Documentation**](https://www.canva.com/design/DAGdpPSgMR4/HBjTMGZK8_qzRB-9XRT7kg/edit?utm_content=DAGdpPSgMR4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)  
[**Tableau Public Dashboard**](https://public.tableau.com/app/profile/aaron.chee6960/viz/LoanApprovalAnalysis_17361390901470/Story1?publish=yes)  

---

## Overview

### Dataset  
**Source**: [Home Loan Approval Dataset (Kaggle)](https://www.kaggle.com/datasets/rishikeshkonapure/home-loan-approval)
- **Size**: 614 rows, 13 columns  
- **Features**:  
  - **Categorical**: Gender, Married, Dependents, Education, Self_Employed, Loan_Amount_Term, Credit_History, Property_Area, Loan_Status  
  - **Numerical**: ApplicantIncome, CoapplicantIncome, LoanAmount  
- **Target Variable**: `Loan_Status` (Approved/Rejected)  

The dataset provides a comprehensive combination of financial, demographic, and credit-related variables critical to analyzing the loan approval process.

---

## Objectives

1. **Data Exploration**: Analyze how income, credit history, and demographics influence loan approval outcomes.  
2. **Storytelling**: Provide an intuitive and interactive narrative to guide stakeholders through key insights.  
3. **Actionable Insights**: Enable better decision-making for applicants, financial institutions, and policymakers.

---

## Process
![image](https://github.com/user-attachments/assets/6dfca087-0a53-4c4f-9884-de00b983b265)
### 1. Data Cleaning & Preprocessing  
Using **Excel**:
- **Imputation**:  
  - Categorical: Mode-based imputation.  
  - Numerical: Median-based imputation to address outliers.  
- **Dynamic Formulas in Excel**:  
  - Mode: `=INDEX(A2:A50, MATCH(MAX(COUNTIF(A2:A50, A2:A50)), COUNTIF(A2:A50, A2:A50), 0))`  
  - Median: `=MEDIAN(A2:A50)`  

![image](https://github.com/user-attachments/assets/574992a6-c0bd-4bcc-876a-30c95b7c5231)
### 2. Feature Engineering  
Using **Excel**:
Key features were added to enhance analysis and storytelling:  
- **Dependents Category**: Grouped as "None," "Single," "Couple," or "Many."  
- **Loan Term Category**: Converted durations (e.g., 360 → "30 years").  
- **Credit History Category**: Grouped into "Good Credit" and "Bad Credit."  
- **Loan Status Category**: Labeled as "Approved" or "Rejected."  
- **Total Income**: Combined Applicant and Coapplicant Income.  
- **Loan Amount per Term**: Loan amount divided by term length to evaluate financial burden.

![image](https://github.com/user-attachments/assets/ba825a1e-8fb0-45cb-b18e-be7dac849be4)
### 3. Exploratory Analysis
Using **SAS Viya**:  
- Created comprehensive visualizations to analyze critical relationships and uncover hidden trends in the dataset.
- Utilized features like Explain Data to derive automated insights and identify anomalies.
- Customized visuals and measures tailored to project objectives, enabling precise and actionable analysis.

![image](https://github.com/user-attachments/assets/66643770-eac8-4aee-ae25-fa71283e9754)
### 4. Data Visualization & Story Telling 
Using **Tableau**:  
- Individual visual & dashboard analyzing credit history, debt-to-income ratio, and demographics.  
- A storytelling dashboard unifying these insights into a cohesive narrative.  

---

## Tableau Storytelling: Dashboards & Insights

![image](https://github.com/user-attachments/assets/19a67e69-7f70-40f1-8f8a-08c30c80076f)
### 6.1 Credit History  
- **Heatmap**:  
  - Approved loan amounts for good credit: **46.17M**.  
  - Approved loan amounts for bad credit: **0.71M**.  
- **Pie Chart**:  
  - Good credit applicants received **85.54%** of the total approved loans, highlighting the importance of creditworthiness.  
- **Key Insight**: Lending criteria could be refined to better meet the needs of applicants with lower credit scores. Special loan products for rejected good-credit applicants could improve approval rates while managing risk.

![image](https://github.com/user-attachments/assets/01f4294a-8a51-43d8-8f50-a252f2767368)
### 6.2 Debt-to-Income Ratio (DTI)  
- Applicants with higher DTIs face higher rejection rates, highlighting financial institutions' preference for manageable debt levels.  
- **Key Insight**:  
  - Longer loan terms could mitigate the impact of high DTIs.  
  - The dashboard emphasizes the interplay between DTI, loan terms, and credit history.  

![image](https://github.com/user-attachments/assets/5e6b88d0-50f2-4a8b-872e-e1d3fc395f86)
### 6.3 Demographics and Risk Level  
- Semi-urban areas had the highest approval rates. Graduates in these areas also saw higher success rates, suggesting a mix of education and local economic conditions influences approvals.  
- **Key Insight**: Policymakers could address demographic disparities through financial literacy programs and targeted support for underserved groups.

---

## Tools & Technologies

- **Excel**: Data cleaning, preprocessing, and feature engineering.  
- **SAS Viya**: Advanced data analysis and visualizations.  
- **Tableau**: Interactive dashboards and storytelling.  

---

## Impact

This project offers:  
- **For Applicants**: Clear insights into loan approval criteria to improve application strategies.  
- **For Financial Institutions**: Opportunities to refine lending policies and create tailored loan products.  
- **For Policymakers**: Data-driven recommendations to promote economic inclusion and responsible lending practices.  

By combining technical skills with a focus on impactful storytelling, this project serves as a testament to my ability to derive actionable insights and present them effectively to diverse stakeholders.

---
