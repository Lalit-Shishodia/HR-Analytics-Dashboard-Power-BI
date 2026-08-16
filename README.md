# 📊 HR Analytics Dashboard --- Employee Attrition & Workforce Analysis

(<img width="1013" height="755" alt="HR Workforce Dashboard" src="https://github.com/user-attachments/assets/f9dad69f-316f-4adf-ab84-9de3d6555f63" />
)

## 📌 Project Overview

This **HR Analytics Dashboard** is an interactive Power BI dashboard
designed to provide an executive-level view of workforce composition,
employee demographics, and attrition.

The dashboard helps HR and business stakeholders understand:

-   Total workforce size and active employees
-   Overall employee attrition
-   Workforce distribution by department
-   Employee age distribution
-   Gender composition
-   Educational background
-   Age-band and gender composition

The project demonstrates an end-to-end **HR Analytics / Business
Intelligence** use case using Power BI, DAX, Power Query, data modeling,
and interactive visualization.

------------------------------------------------------------------------

## 🎯 Business Objective

The primary objective is to transform employee-level HR data into
actionable insights that can support:

-   Workforce planning
-   Employee retention
-   Attrition monitoring
-   Talent management
-   Diversity analysis
-   Workforce segmentation
-   HR decision-making

The dashboard is designed to answer the most important question:

> **"What does our workforce look like, how much attrition are we
> experiencing, and which employee segments require deeper
> investigation?"**

------------------------------------------------------------------------

## 📈 Executive KPI Summary

  ------------------------------------------------------------------------
  KPI                                          Value Business Meaning
  --------------------- ---------------------------- ---------------------
  **Total Employee                         **1,470** Total employees
  Count**                                            represented in the
                                                     dataset

  **Attrition Count**                        **237** Employees who have
                                                     exited

  **Attrition Rate**                      **16.12%** Overall percentage of
                                                     employees who exited

  **Active Employees**                     **1,233** Employees remaining
                                                     active

  **Average Age**                       **37 years** Average employee age
  ------------------------------------------------------------------------

### Attrition Rate

The dashboard reports an attrition rate of **16.12%**.

``` text
Attrition Rate =
Attrition Count / Total Employee Count × 100

= 237 / 1470 × 100
≈ 16.12%
```

This means approximately **16 out of every 100 employees** are
represented as attrition cases.

------------------------------------------------------------------------

# 🔎 Key Business Insights

## 1. Overall Workforce & Attrition

The organization has a workforce of **1,470 employees**, of which:

-   **1,233 employees are active**
-   **237 employees are recorded as attrition**
-   **16.12% overall attrition rate**

The active workforce represents approximately **83.88%** of the total
employee population.

### Business implication

A 16.12% attrition rate deserves deeper diagnostic analysis. HR should
investigate whether exits are concentrated among particular:

-   Departments
-   Job roles
-   Age groups
-   Tenure groups
-   Income levels
-   Overtime patterns
-   Satisfaction levels
-   Promotion histories

------------------------------------------------------------------------

## 2. Department Attrition Distribution

The department visual shows the following Attrition Distribution:

  Department     Attrition Share
  ------------ -----------------
  **R&D**             **56.12%**
  **Sales**           **38.82%**
  **HR**               **5.06%**

R&D represents the largest Attrition segment, followed by Sales and HR.

### Business implication

Because R&D and Sales together represent almost **95% of the
Attrition**, workforce stability in these two departments can have a
major effect on overall organizational performance.


------------------------------------------------------------------------

## 3. Workforce is Concentrated Around Ages 25--44

The dashboard shows a strong concentration of employees in the **25--44
age range**.

  Age Band         Female   Male     Total
  -------------- -------- ------ ---------
  **25--34**          217    337   **554**
  **35--44**          196    309   **505**
  **45--54**          113    132   **245**
  **Under 25**         37     60    **97**
  **Over 55**          25     44    **69**

Employees aged **25--44 total 1,059 employees**, representing
approximately **72.0% of the workforce**.

### Business implication

The organization is heavily dependent on early- and mid-career talent.

HR could therefore focus on:

-   Career development
-   Internal mobility
-   Promotion opportunities
-   Compensation benchmarking
-   Training programs
-   Work-life balance
-   Employee engagement

for these age groups.

------------------------------------------------------------------------

## 4. Gender Distribution

The dashboard shows:

-   **Male: 882 employees --- 60%**
-   **Female: 588 employees --- 40%**

This represents a **60:40 male-to-female workforce distribution**.

### Business implication

The gender view provides a useful foundation for deeper analysis of:

-   Attrition rate by gender
-   Promotion rate by gender
-   Compensation differences
-   Job-role distribution
-   Career progression
-   Workforce representation

The current dashboard shows workforce composition; a future version
should compare **attrition rates**, rather than only employee counts, by
gender.

------------------------------------------------------------------------

## 5. Education Profile

The workforce has the following education distribution:

  Education                Employees
  ---------------------- -----------
  **Life Sciences**          **606**
  **Medical**                **464**
  **Marketing**              **159**
  **Technical Degree**       **132**
  **Other**                   **82**
  **Human Resources**         **27**

Life Sciences and Medical backgrounds together account for:

**606 + 464 = 1,070 employees**

This represents approximately **72.8% of the total workforce**.

### Business implication

The workforce has a strong concentration in specialized educational
backgrounds.

HR can use this information for:

-   Workforce capability planning
-   Skill-gap analysis
-   Internal mobility
-   Training and development
-   Hiring strategy
-   Succession planning

------------------------------------------------------------------------

# 📊 Dashboard Visual Analysis

## KPI Cards

The top section provides five executive KPIs:

1.  Total Employee Count
2.  Attrition Count
3.  Attrition %
4.  Active Employees
5.  Average Age

This provides an effective **executive summary layer** before users move
into detailed visual analysis.

------------------------------------------------------------------------

## Department Analysis

The department chart provides a quick understanding of workforce
concentration.

Recommended enhancement:

-   Employee Count
-   Attrition Count
-   Attrition Rate
-   Active Employee Count

should be available together for department-level comparison.

------------------------------------------------------------------------

## Age Distribution

The age histogram shows the highest employee concentration around the
**late 20s to late 30s**.

This suggests a relatively young-to-mid-career workforce profile.

Recommended enhancement:

Add an **Attrition Rate by Age Band** visual to determine whether
younger employees actually have higher turnover.

------------------------------------------------------------------------

## Gender Analysis

The gender donut chart provides a quick workforce composition view.

Recommended enhancement:

Replace or complement the current chart with:

``` text
Gender
├── Employee Count
├── Attrition Count
└── Attrition Rate
```

This makes the analysis more actionable.

------------------------------------------------------------------------

## Education Analysis

The horizontal bar chart clearly identifies the largest educational
groups.

The visualization is particularly useful for workforce planning because
it highlights the organization's dominant talent backgrounds.

------------------------------------------------------------------------

# 🧠 Recommended Advanced HR Analysis

The current dashboard is primarily **descriptive analytics**.

To make the project stronger for a professional portfolio, extend it
into **diagnostic and predictive analytics**.

### Attrition Drivers

Analyze attrition against:

-   Job Role
-   Department
-   Age
-   Gender
-   Education
-   Years at Company
-   Years in Current Role
-   Monthly Income
-   Job Level
-   Overtime
-   Job Satisfaction
-   Environment Satisfaction
-   Work-Life Balance
-   Business Travel
-   Distance From Home
-   Years Since Last Promotion
-   Performance Rating

### Recommended Questions

**Who is leaving?**

-   Which age group has the highest attrition?
-   Which job roles have the highest attrition?
-   Is attrition concentrated among new employees?

**Why are employees leaving?**

-   Does overtime increase attrition?
-   Does low job satisfaction correlate with attrition?
-   Does lower compensation correlate with attrition?
-   Does lack of promotion contribute to exits?

**Where should HR act?**

-   Which departments require retention programs?
-   Which employee segments are high-risk?
-   Which roles require stronger career development?
-   Which groups need compensation or engagement interventions?

------------------------------------------------------------------------

# 🧮 Recommended DAX Measures

### Total Employees

``` dax
Total Employees =
COUNTROWS(Employee)
```

### Attrition Count

``` dax
Attrition Count =
CALCULATE(
    COUNTROWS(Employee),
    Employee[Attrition] = "Yes"
)
```

### Active Employees

``` dax
Active Employees =
CALCULATE(
    COUNTROWS(Employee),
    Employee[Attrition] = "No"
)
```

### Attrition Rate

``` dax
Attrition Rate =
DIVIDE(
    [Attrition Count],
    [Total Employees],
    0
)
```

Format this measure as **Percentage**.

### Average Age

``` dax
Average Age =
AVERAGE(Employee[Age])
```

### Department Attrition Count

``` dax
Department Attrition Count =
CALCULATE(
    [Attrition Count],
    ALLEXCEPT(
        Employee,
        Employee[Department]
    )
)
```

### Department Attrition Rate

``` dax
Department Attrition Rate =
DIVIDE(
    [Department Attrition Count],
    [Total Employees],
    0
)
```

------------------------------------------------------------------------

# 🏗️ Power BI Dashboard Architecture

## Page 1 --- HR Workforce Overview

### KPI Layer

-   Total Employees
-   Attrition Count
-   Attrition %
-   Active Employees
-   Average Age

### Workforce Layer

-   Employee Distribution by Department
-   Employee Distribution by Age
-   Employee Distribution by Gender
-   Employee Count by Education
-   Age Band & Gender Distribution

### Filter Layer

-   Education

------------------------------------------------------------------------

## 🚀 Recommended Future Dashboard Pages

### Page 2 --- Attrition Analysis

-   Attrition Rate by Department
-   Attrition Rate by Job Role
-   Attrition Rate by Age Band
-   Attrition Rate by Gender
-   Attrition by Education
-   Attrition Trend

### Page 3 --- Attrition Drivers

-   Attrition vs Overtime
-   Attrition vs Job Satisfaction
-   Attrition vs Monthly Income
-   Attrition vs Years at Company
-   Attrition vs Promotion
-   Attrition vs Work-Life Balance

### Page 4 --- Employee Segmentation

-   High-risk employee segments
-   Tenure groups
-   Job-level analysis
-   Income bands
-   Performance groups
-   Business travel segments

------------------------------------------------------------------------

# 🎨 Dashboard Design Approach

The dashboard uses an executive-style layout:

``` text
┌───────────────────────────────────────────────────────┐
│              HR ANALYTICS DASHBOARD                   │
│                                    Education Filter  │
├───────────────────────────────────────────────────────┤
│ Total │ Attrition │ Attrition % │ Active │ Avg Age   │
├───────────────────┬─────────────────┬────────────────┤
│ Department        │ Age Distribution│ Gender         │
│ Distribution      │                 │ Distribution   │
├───────────────────┴─────────────────┴────────────────┤
│ Education Distribution │ Age Band & Gender           │
└───────────────────────────────────────────────────────┘
```

The design prioritizes:

-   Executive KPIs at the top
-   Demographic analysis in the middle
-   Workforce segmentation at the bottom
-   Minimal navigation complexity
-   Consistent visual formatting

------------------------------------------------------------------------

# 🛠️ Tools & Technologies

  Technology          Purpose
  ------------------- ------------------------------------------
  **Power BI**        Dashboard development and visualization
  **DAX**             KPI calculations and analytical measures
  **Power Query**     Data cleaning and transformation
  **Data Modeling**   Relationships and analytical structure
  **Excel / CSV**     Data source and data preparation

------------------------------------------------------------------------

# 📂 Recommended GitHub Repository Structure

``` text
HR-Analytics-PowerBI/
│
├── README.md
│
├── Dashboard/
│   └── HR_Analytics_Dashboard.pbix
│
├── Data/
│   └── HR_Employee_Data.csv
│
├── Screenshots/
│   └── HR Dashboard.PNG
│
├── DAX/
│   └── HR_KPI_Measures.txt
│
└── Documentation/
    └── HR_Analytics_Report.pdf
```

------------------------------------------------------------------------

# 📌 Data Quality & Dashboard Improvements

Before presenting this dashboard as an executive HR solution, the
following improvements are recommended:

### 1. Correct Department Chart Label

Change:

**Attrition by Department**

to:

**Employee Distribution by Department**

unless the measure is changed to actual department attrition.

### 2. Add Department Attrition Rate

A large department may naturally have more attrition cases simply
because it has more employees.

Always compare:

``` text
Attrition Count
        ÷
Department Employee Count
        × 100
```

### 3. Add Attrition Trend

Add a monthly or quarterly trend to understand whether attrition is:

-   Increasing
-   Decreasing
-   Stable
-   Seasonal

### 4. Add Attrition Drivers

Include overtime, tenure, job satisfaction, compensation, promotion,
business travel, and work-life balance.

### 5. Add Drill-through

Create an employee-segment drill-through page for HR users to
investigate high-risk groups without overcrowding the main dashboard.

### 6. Improve Chart Titles

Use precise business terminology:

-   Employee Distribution by Department
-   Employee Distribution by Gender
-   Employee Count by Age
-   Employee Count by Education
-   Employee Count by Age Band & Gender

This makes the dashboard easier for business users to interpret.

------------------------------------------------------------------------

# 💼 Business Impact

This dashboard can help HR teams:

-   Monitor workforce health
-   Track employee attrition
-   Understand workforce demographics
-   Identify major workforce segments
-   Support workforce planning
-   Prioritize retention initiatives
-   Identify areas requiring deeper investigation
-   Build data-driven HR strategies

The dashboard provides the **descriptive layer** of HR analytics. Adding
attrition drivers and predictive modeling can transform it into a
complete **HR decision-support solution**.

------------------------------------------------------------------------

# ⭐ Portfolio Value

This project demonstrates practical skills in:

**Power BI \| DAX \| Power Query \| Data Modeling \| HR Analytics \|
Workforce Analytics \| Attrition Analysis \| KPI Development \| Data
Visualization \| Business Intelligence \| Business Insights**

It is particularly useful as a portfolio project because it demonstrates
that the analysis goes beyond simply creating charts: the dashboard
connects **KPIs → workforce patterns → business interpretation →
recommended HR actions**.

------------------------------------------------------------------------

# 📌 Conclusion

The HR Analytics Dashboard provides a clear overview of a
**1,470-employee workforce** with **237 attrition cases** and a reported
**16.12% attrition rate**.

The analysis shows that:

-   **R&D represents 56.12%** of the workforce.
-   **Sales represents 38.82%**.
-   **25--44-year-old employees represent approximately 72%** of the
    workforce.
-   The workforce is **60% male and 40% female**.
-   **Life Sciences and Medical backgrounds represent approximately
    72.8%** of employees.
-   The organization has **1,233 active employees**.

The most valuable next step is to move beyond workforce composition and
determine **which employee segments have the highest attrition and
why**.

That can be achieved by combining department, job role, age, tenure,
compensation, overtime, satisfaction, promotion, and performance data
into a deeper **attrition-driver and employee-retention analysis**.

------------------------------------------------------------------------

## 👨‍💻 Project Skills

`Power BI` `DAX` `Power Query` `Data Modeling` `HR Analytics`
`Attrition Analytics` `Workforce Analytics` `KPI Development`
`Data Visualization` `Business Intelligence` `Business Analysis`
