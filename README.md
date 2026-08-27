# 📊 Employee Turnover Rate Analysis
## Introduction
We work as People Analysts for a Life Sciences company, and corporate has asked us to identify employees with a higher risk of attrition.
This project features interactive dashboards designed in Tableau to analyze employee turnover rates & behaviour. The main objective is to identify patterns, evaluate risk factors, and uncover the root causes driving talent attrition within the organization.

The main question we aim to answer is: **Which employees present the highest flight risk?**

## 🛠️ Data
**Source:** For this analysis, we used the "HR Analytics Employee Attrition & Performance" dataset, sourced from Kaggle.
**Cleaning and Transformation:** The data was processed in Tableau by selecting the relevant columns, removing null values, and transforming parameters.

---

## **DASHBOARD 1 - Attrition filtered by department**
[![Dashboard Preview](attrition.png)](https://public.tableau.com/app/profile/marc.mateu.higueras/viz/Attrition_Department/Dashboard1)

### 🎯 Analysis Objectives
* **Identify** departments or roles with the highest turnover rates.
* **Analyze** demographic and workplace variables (salary & job satisfaction) that impact employee retention.
* **Provide** actionable insights for Human Resources (HR) teams to improve retention strategies.

### 🔍 Dashboard 1: Key Findings and conclusions
* The highest turnover rate is found in the Sales department at 20.63%. Overall, 54.55% of the employees in the 1K monthly income bin has left the company. Additionally, 22.84% of the employees reportiong the lowest job satisfaction score have attrited.
* In sales department, income highly explains the attrition, showing an 80% turnover rate in the 1K salary bin. In the HR department, the most influential factor is job satisfaction, wich drives a 45.45% attrition rate at lowest job satisfaction level (excluding income outliers consisting of only 1 or 2 employees). In Research & Development department, the salary is also the primary factor, showing 40.91% attrition rate in the 1k bin.
* We can conclude that, across most departments, low salary (specifically within the 1K bracket) is the most consistent driver of attrition. However, the HR department stands out as an exception, where poor job satisfaction is the most critical risk factor for turnover.

**Hypothesis:** Preliminary observations suggest that employees with fewer years at the company exhibit the highest turnover rates, assuming that lower salaries generally correlate with newer employees. To properly validate this hypothesis and investigate the exact relationship between time spent at the company and flight risk, we will develop a second dashboard dedicated to this metric.

## **DASHBOARD 2 - Year of attrition filtered by role**
[![Dashboard Preview](turnover_role.png)](https://public.tableau.com/app/profile/marc.mateu.higueras/viz/Dashboard_Rotacin_Empleados/Dashboard2)

### 🎯 Analysis Objectives
* **Identify** years at company with higher turnover rate and percentage of attrition.
* **Analyze** the influence of the job role on employee retention.
* **To carry on** retention strategies at target employees.


👉 **[Click here to view more interactive dashboards on my profile of Tableau Public](https://public.tableau.com/app/profile/marc.mateu.higueras/viz/Dashboard_Rotacin_Empleados/Dashboard1?publish=yes)**

---

### 🛠️ Tools Used
* **Tableau:** Data visualization and dashboard creation.
* **Git & GitHub:** Version control and portfolio hosting.
