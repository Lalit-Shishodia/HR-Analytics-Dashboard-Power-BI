# 👥 HR Workforce Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge\&logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-Measures-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green?style=for-the-badge)
![HR Analytics](https://img.shields.io/badge/Domain-HR%20Analytics-purple?style=for-the-badge)

## 📌 Project Overview

The **HR Workforce Analytics Dashboard** is an interactive Power BI business intelligence solution designed to provide management with a comprehensive view of **employee workforce composition, attrition, demographics, education, age distribution, and gender diversity**.

The dashboard transforms employee-level HR data into actionable workforce insights that can support **employee retention, workforce planning, talent management, diversity analysis, and HR decision-making**.

---

## 🎯 Business Objective

The primary objective of this project is to help HR leadership answer critical workforce questions:

* How large is the current workforce?
* What percentage of employees have left the organization?
* Which departments have the highest workforce concentration?
* What is the organization's age distribution?
* Which age groups represent the largest workforce segments?
* What is the male-to-female workforce distribution?
* Which educational backgrounds dominate the workforce?
* How is gender distributed across different age bands?
* Which workforce segments may require deeper attrition analysis?
* How can HR teams use workforce demographics for better planning?

---

## 📊 Dashboard Overview

The dashboard contains the following major KPI cards and visualizations:

### 🔹 Key KPIs

| KPI                  |      Value |
| -------------------- | ---------: |
| Total Employees      |  **1,470** |
| Attrition Count      |    **237** |
| Attrition Rate       | **16.12%** |
| Active Employees     |  **1,233** |
| Average Employee Age |     **37** |

### 🔹 Dashboard Visuals

1. **Employee Distribution by Department**
2. **Employee Count by Age**
3. **Employee Distribution by Gender**
4. **Employee Count by Education**
5. **Employee Count by Age Band & Gender**
6. **Education Filter**
7. Workforce-level KPI cards

---

## 🔎 Key Business Insights

### 1. Workforce Size & Attrition

The organization has **1,470 employees**, with **237 employees recorded as attrition**, resulting in an overall attrition rate of approximately **16.12%**.

This indicates that employee retention should be monitored closely, particularly by department, tenure, job level, compensation, performance, and employee satisfaction.

### 2. Active Workforce

The dashboard shows **1,233 active employees**, representing the majority of the current workforce.

HR management can use this metric as the baseline for:

* Workforce planning
* Hiring requirements
* Capacity planning
* Employee retention strategies
* Headcount forecasting

### 3. Department Workforce Concentration

The workforce is highly concentrated in the **R&D department**, which accounts for approximately **65.37%** of employees.

Sales represents approximately **30.34%**, while HR represents around **4.29%**.

This concentration makes R&D a particularly important segment for workforce planning and retention analysis.

### 4. Gender Distribution

The workforce consists of approximately:

* **882 Male employees — 60%**
* **588 Female employees — 40%**

The relatively balanced representation provides an opportunity to further analyze:

* Gender-specific attrition
* Promotion rates
* Compensation
* Career progression
* Leadership representation
* Employee engagement

### 5. Age Distribution

The workforce is concentrated primarily around the **late-20s to late-30s age range**.

Employees in their **30s represent one of the largest workforce segments**, making this group particularly important for:

* Career development
* Retention programs
* Leadership pipeline planning
* Skill development
* Succession planning

### 6. Education Profile

The workforce has a diverse educational background.

| Education        | Employees |
| ---------------- | --------: |
| Life Sciences    |       606 |
| Medical          |       464 |
| Marketing        |       159 |
| Technical Degree |       132 |
| Other            |        82 |
| Human Resources  |        27 |

**Life Sciences** represents the largest educational group, followed by **Medical**.

This information can help HR teams evaluate whether workforce skills and educational backgrounds align with organizational requirements.

### 7. Age Band & Gender Analysis

The **25–34** and **35–44** age bands contain the largest number of employees.

This suggests that the organization has a relatively strong concentration of **early-to-mid-career professionals**.

HR can use this insight to design:

* Career progression programs
* Leadership development
* Internal mobility programs
* Skill development initiatives
* Retention strategies

---

## 🛠️ Tools & Technologies

### Business Intelligence

* **Microsoft Power BI**
* Power BI Desktop

### Data Preparation

* **Power Query**
* Data Cleaning
* Data Transformation
* Data Validation

### Data Modeling

* Star Schema principles
* Relationships
* Calculated Columns
* Measures
* Dimension-based analysis

### Analytics

* **DAX**
* KPI Analysis
* Segmentation
* Workforce Demographics
* Attrition Analysis

---

## 🔄 End-to-End Project Workflow

```text
Raw HR Dataset
      ↓
Data Profiling
      ↓
Data Cleaning
      ↓
Power Query Transformation
      ↓
Data Modeling
      ↓
Relationship Creation
      ↓
DAX Measures
      ↓
KPI Development
      ↓
Dashboard Design
      ↓
Workforce Segmentation
      ↓
Business Insights
      ↓
HR Decision Support
```

---

## 🧹 Data Preparation Process

The following data preparation activities can be performed before dashboard development:

* Removed duplicate employee records
* Checked missing values
* Validated employee IDs
* Standardized categorical fields
* Validated age values
* Standardized department names
* Validated education categories
* Created age bands
* Created income bands
* Created performance groups
* Created attrition flags
* Checked relationship consistency
* Validated KPI calculations

---

## 🎨 Dashboard Design Principles

The dashboard was designed using a management-focused approach:

* Executive KPI cards at the top
* Clear visual hierarchy
* Consistent color palette
* Interactive slicers
* Minimal visual clutter
* Business-oriented chart titles
* Department-level comparison
* Demographic segmentation
* Easy-to-understand KPI presentation

---

## 💡 Business Value

This dashboard can help HR and management teams:

✅ Monitor overall workforce health
✅ Track employee attrition
✅ Identify workforce concentration
✅ Understand employee demographics
✅ Support workforce planning
✅ Analyze gender distribution
✅ Understand educational composition
✅ Identify critical workforce segments
✅ Develop targeted retention strategies
✅ Support data-driven HR decisions

---

## 🚀 Future Enhancements

### Workforce Planning

* Headcount forecasting
* Hiring requirements
* Workforce capacity
* Retirement projections

Potential risk factors:

* Low job satisfaction
* Low income
* High overtime
* Frequent business travel
* Short tenure
* Poor performance
* Limited career progression

### Predictive Analytics

The Power BI solution can eventually be integrated with Python/Machine Learning to build:

* Employee Attrition Prediction
* Employee Risk Scoring
* Workforce Demand Forecasting
* Employee Segmentation
* Retention Recommendation Models

---

## 📁 Suggested GitHub Repository Structure

```text
HR-Workforce-Analytics/
│
├── Dataset/
│   └── employee_data.csv
│
├── PowerBI/
│   └── HR_Workforce_Dashboard.pbix
│
├── Screenshots/
│   └── HR_Workforce_Dashboard.png
│
├── Documentation/
│   ├── Business_Requirements.md
│   ├── KPI_Definitions.md
│   └── Data_Dictionary.md
│
├── DAX/
│   └── HR_Measures.dax
│
└── README.md
```

---

## 📌 Project Highlights

**Domain:** Human Resources / Workforce Analytics

**Project Type:** Business Intelligence & Data Analytics

**Primary Tool:** Microsoft Power BI

**Key Skills:** Power Query, DAX, Data Modeling, KPI Development, Data Visualization, Workforce Analytics

**Key Business Areas:** Workforce Planning, Employee Attrition, Demographics, Diversity, Employee Segmentation

---

## 👨‍💻 Author

**Lalit Shishodia**

Data Analyst | Power BI | SQL | Python | Data Analytics | Machine Learning

This project demonstrates the application of **business intelligence and data analytics techniques to solve real-world HR workforce management problems**.

---

## ⭐ If You Like This Project

If you find this project useful, consider giving the repository a ⭐ and connecting with me for discussions around **Power BI, SQL, Data Analytics, and Machine Learning**.


## 👨‍💻 Project Skills

`Power BI` `DAX` `Power Query` `Data Modeling` `HR Analytics`
`Attrition Analytics` `Workforce Analytics` `KPI Development`
`Data Visualization` `Business Intelligence` `Business Analysis`
