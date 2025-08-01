# HR Analytics Dashboard

**Tableau dashboard exploring attrition forecasting and workforce insights using a sample HR dataset**

![HR Dashboard](Dashboard_Screenshot.png)

## **Executive Summary**

This HR analytics project offers an in-depth exploration into attrition patterns across departments, roles, and employee demographics. Through six visualizations, it identifies key factors associated with employee turnover such as job role, gender, overtime, commute distance, and promotion history. The analysis reveals high-risk areas including Laboratory Technicians, long-distance commuters, and employees with delayed promotions. Recommendations are provided to mitigate attrition risks and guide strategic workforce planning.

## **About the Company**

Yello is a mid-sized company with a diverse workforce across departments like Sales, Research & Development (R&D), and Human Resources.  
Employees vary in roles, educational backgrounds, and career paths.

To support effective strategic planning, Yello aims to analyze salary trends, workforce demographics, and retention patterns.  
By leveraging data-driven insights, the company seeks to improve decisions related to compensation, training, and employee retention.

## **Problem Statement**

Yello requires an in-depth analysis of employee income trends and workforce demographics to enhance financial planning and retention strategies.

- Identify salary distribution patterns
- Predict attrition risks
- Examine how job role, department, distance, and promotion affect attrition
- Visualize metrics to extract actionable business insights

## **Aims of the Project**

- Forecast attrition risks
- Identify employee clusters at risk based on promotion and distance
- Uncover department and role-specific trends
- Explore key KPIs such as job satisfaction and overtime patterns

## **Files Included**

| File                               | Description                                         |
|------------------------------------|-----------------------------------------------------|
| HR_Analytics_Dashboard.twbx        | Packaged Tableau Workbook with dashboard            |
| HR_Data_Cleaned_Table_1.xlsx       | Cleaned Excel source (Table 1)                      |
| HR_Data_Cleaned_Table_2.xlsx       | Cleaned Excel source (Table 2)                      |
| HR_Data_Cleaned_Table_3.xlsx       | Cleaned Excel source (Table 3)                      |
| Dashboard_Screenshot.png           | Static preview of dashboard                         |
| README.md                          | This documentation file                             |
| attritionbydepartment.png          | Chart: Attrition By Department                      |
| attritionbyjobrole.png             | Chart: Attrition By Job Role                        |
| attritionbygenderanddepartment.png| Chart: Attrition by Gender & Department             |
| attritionbyjobsatisfactionandemployeecount.png | Chart: Job Satisfaction vs Attrition     |
| attritionratebyjobroleandovertime.png | Chart: Attrition Rate by Job Role and OT       |
| attritionbycommuteandpromotion.png | Chart: Attrition by Commute Distance & Promotion    |

## **Deep-Dive Visualizations & Insights**

### **1. Attrition by Department**
![Attrition by Department](attritionbydepartment.png)

- R&D has the highest attrition count (133), followed by Sales (92).  
- HR has significantly lower attrition (12), indicating stronger retention or smaller department size.  
- High attrition in R&D signals possible issues with workload, compensation, or advancement opportunities.

### **2. Attrition by Job Role**
![Attrition by Job Role](attritionbyjobrole.png)

- Laboratory Technicians, Sales Executives, and Research Scientists account for the highest attrition.  
- Roles with lower attrition such as Directors and Managers may offer more stability or benefits.

### **3. Attrition by Gender & Department**
![Attrition by Gender and Department](attritionbygenderanddepartment.png)

- Attrition is generally higher for male employees, especially in R&D (90 males vs 43 females).  
- HR shows balanced gender attrition, but numbers are small.  
- Gender-based policies may be needed in technical departments.

### **4. Attrition by Job Satisfaction & Employee Count**
![Attrition by Job Satisfaction](attritionbyjobsatisfactionandemployeecount.png)

- Employees with low job satisfaction (1 or 2) show visibly higher attrition rates.  
- Satisfaction level 3 has the highest count of departing employees, suggesting it's a danger zone for disengagement.

### **5. Attrition by Job Role & Overtime**
![Attrition by Job Role & OT](attritionratebyjobroleandovertime.png)

- Roles with mandatory overtime (OT) show consistently higher attrition rates.  
- Research Scientists and Laboratory Technicians with OT have attrition over 13%.  
- Overwork may be a driving factor for turnover.

### **6. Attrition by Commute Distance & Promotion Concerns**
![Attrition by Commute and Promotion](attritionbycommuteandpromotion.png)

- High attrition clusters in the upper-right quadrant: long commute and many years since last promotion.  
- Employees with both issues are categorized “High Risk”.  
- “Commute Concern” and “Promotion Concern” quadrants show moderate attrition patterns.

## **Recommendations**

- Implement promotion readiness assessments and leadership training to support internal growth.
- Introduce remote work or flexible commute programs for long-distance employees.
- Review overtime policies and workloads in scientific/technical departments.
- Conduct regular job satisfaction surveys with follow-up actions.
- Enhance onboarding and support systems for roles with high turnover.

## **Assumptions**

- All visualizations are based on cleaned and joined data across three HR tables.
- Attrition is considered voluntary unless otherwise stated.
- Satisfaction, overtime, and distance values are assumed to be self-reported or recorded internally.
- All calculated rates are relative to available data and may vary in full population.

## **Next Steps**

- Incorporate machine learning for predictive attrition modeling.
- Segment analysis by tenure, education, or team manager.
- Gather exit interview feedback to validate data findings.
- Add salary and performance review variables for deeper behavioral trends.

## **About the Data**

This project uses anonymized HR data structured across three tables, joined in Tableau.  
Columns include employee demographics, satisfaction ratings, job roles, attrition flags, and commute information.

## **Disclaimer**

This project is for portfolio and educational display only.  
No content may be copied, reproduced, or reused without permission.

## **Connect With Me**

- LinkedIn: [linkedin.com/in/desireesalvant](https://linkedin.com/in/desireesalvant)
- GitHub: [github.com/DesireeSalvant](https://github.com/DesireeSalvant)
- Portfolio: [desireesalvant.com](https://desireesalvant.com) *(Coming soon!)*
- Tableau Public: [View My Tableau Public Projects](https://public.tableau.com/app/profile/desireesalvant)

