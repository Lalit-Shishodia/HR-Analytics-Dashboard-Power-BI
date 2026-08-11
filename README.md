# 📊 HR Analytics & Employee Attrition Dashboard

![HR Analytics Dashboard](HR%20Attrition%20Dashboard.PNG)

## 📌 Project Overview

This **HR Analytics Dashboard** is an interactive Power BI project
designed to analyze employee demographics, workforce composition, and
employee attrition patterns.

The dashboard provides HR stakeholders with a high-level view of:

-   Total workforce and active employees
-   Employee attrition volume and attrition rate
-   Workforce distribution by department
-   Employee age distribution
-   Gender composition
-   Education background
-   Age-band and gender composition

The objective is to help HR teams identify workforce concentration,
demographic patterns, and potential areas requiring deeper attrition
investigation.

------------------------------------------------------------------------

## 🎯 Business Objectives

The analysis focuses on answering key HR questions:

1.  How large is the current workforce?
2.  How many employees have left the organization?
3.  What is the overall attrition rate?
4.  Which departments contain the largest share of employees?
5.  Which age groups represent the core workforce?
6.  What is the gender composition of employees?
7.  What educational backgrounds are most common?
8.  How does gender distribution vary across age bands?
9.  Where should HR focus further attrition analysis and retention
    initiatives?

------------------------------------------------------------------------

## 📈 Executive KPI Summary

  ------------------------------------------------------------------------
  KPI                                          Value Interpretation
  --------------------- ---------------------------- ---------------------
  Total Employees                          **1,470** Total workforce
                                                     represented in the
                                                     dataset

  Attrition Count                            **237** Employees who have
                                                     left

  Attrition Rate                          **16.12%** Overall employee
                                                     attrition

  Active Employees                         **1,233** Employees currently
                                                     active

  Average Age                           **37 years** Average employee age
  ------------------------------------------------------------------------

### Key KPI Formula

**Attrition Rate**

``` text
Attrition Rate = Attrition Count / Total Employee Count × 100
```

``` text
= 237 / 1470 × 100
≈ 16.12%
```

------------------------------------------------------------------------

## 🔎 Key Business Insights

### 1. Overall Attrition

The organization has **237 attrition cases out of 1,470 employees**,
resulting in an overall attrition rate of **16.12%**.

This indicates that approximately **1 out of every 6 employees** has
exited the organization during the period represented by the dataset.

> **Business implication:** HR should investigate the major drivers
> behind exits, particularly by department, age group, job role, tenure,
> compensation, job satisfaction, and overtime.

------------------------------------------------------------------------

### 2. Workforce is Highly Concentrated in R&D

The department distribution shown in the dashboard is:

  Department     Workforce Share
  ------------ -----------------
  R&D                 **65.37%**
  Sales               **30.34%**
  HR                   **4.29%**

R&D represents nearly **two-thirds of the workforce**, making it the
largest employee population.

> **Business implication:** Because R&D has the largest employee base,
> even a moderate attrition rate in this department could create a
> significant number of employee exits and replacement costs.

⚠️ **Dashboard note:** The visual is titled **"Attrition by
Department"**, but the percentages shown add up to the total workforce
distribution rather than the distribution of the 237 attrition cases.
For a true attrition-by-department analysis, use:

``` text
Department Attrition Rate =
Department Attrition Count / Department Employee Count × 100
```

------------------------------------------------------------------------

### 3. Workforce is Concentrated Between Ages 25--44

The age-band chart shows:

  Age Band     Female   Male     Total
  ---------- -------- ------ ---------
  25--34          217    337   **554**
  35--44          196    309   **505**
  45--54          113    132   **245**
  Under 25         37     60    **97**
  Over 55          25     44    **69**

Employees aged **25--44 account for 1,059 employees**, or approximately
**72% of the total workforce**.

> **Business implication:** Retention strategies for early- and
> mid-career employees could have a major impact on workforce stability.

------------------------------------------------------------------------

### 4. Gender Distribution

The workforce consists of:

-   **882 Male employees --- 60%**
-   **588 Female employees --- 40%**

The workforce therefore has a **60:40 male-to-female distribution**.

> **Business implication:** HR can use gender-level analysis to
> investigate whether attrition, promotion, compensation, job
> satisfaction, or career progression differs between employee groups.

------------------------------------------------------------------------

### 5. Education Profile

The largest employee groups by education background are:

  Education Field      Employees
  ------------------ -----------
  Life Sciences          **606**
  Medical                **464**
  Marketing              **159**
  Technical Degree       **132**
  Other                   **82**
  Human Resources         **27**

**Life Sciences and Medical backgrounds together account for 1,070
employees**, representing approximately **73% of the workforce**.

> **Business implication:** The organization has a highly specialized
> workforce. Talent planning, internal mobility, and role-specific
> career development can therefore be important retention levers.

------------------------------------------------------------------------

## 💡 Recommended HR Analysis

The current dashboard provides a strong workforce overview, but
attrition decisions should be supported by additional dimensions.

### Recommended next-level analysis

-   Attrition by **Job Role**
-   Attrition by **Department**
-   Attrition by **Age Band**
-   Attrition by **Gender**
-   Attrition by **Education**
-   Attrition by **Years at Company**
-   Attrition by **Job Level**
-   Attrition by **Monthly Income**
-   Attrition by **Overtime**
-   Attrition by **Job Satisfaction**
-   Attrition by **Work-Life Balance**
-   Attrition by **Distance from Home**
-   Attrition by **Business Travel**
-   Attrition by **Performance Rating**
-   Attrition by **Years Since Last Promotion**

This would allow HR to move from **descriptive analytics** ("what
happened?") toward **diagnostic analytics** ("why did it happen?").

------------------------------------------------------------------------

## 🧠 Potential Business Questions

The dashboard can be extended to answer questions such as:

### Workforce

-   Which department has the largest workforce?
-   What is the organization's demographic profile?
-   Which age groups represent the largest employee population?

### Attrition

-   Which department has the highest attrition rate?
-   Which job roles have the highest employee turnover?
-   Are younger employees leaving more frequently?
-   Does overtime correlate with higher attrition?
-   Does lower job satisfaction correspond to increased attrition?

### Retention

-   Are employees with longer tenure less likely to leave?
-   Does compensation influence attrition?
-   Are employees with fewer promotion opportunities more likely to
    exit?
-   Which employee segments should HR prioritize for retention programs?

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Power BI** --- Dashboard development and visualization
-   **Power Query** --- Data cleaning and transformation
-   **DAX** --- KPI and analytical measure creation
-   **Data Modeling** --- Relationships and analytical structure
-   **Excel / CSV** --- Data source and initial data preparation

------------------------------------------------------------------------

## 📊 Power BI Measures

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

Format the measure as **Percentage**.

### Average Age

``` dax
Average Age =
AVERAGE(Employee[Age])
```

------------------------------------------------------------------------

## 🏗️ Dashboard Structure

### Page 1 --- HR Workforce Overview

**KPIs** - Total Employees - Attrition Count - Attrition % - Active
Employees - Average Age

**Visuals** - Workforce by Department - Employee Count by Age - Employee
Count by Gender - Employee Count by Education - Age Band & Gender
Analysis

**Slicer** - Education

------------------------------------------------------------------------

## 🎨 Dashboard Design

The dashboard follows a clean executive-reporting structure:

``` text
┌─────────────────────────────────────────────────────┐
│                 HR ANALYTICS DASHBOARD               │
│                           Education Filter            │
├─────────────────────────────────────────────────────┤
│ Total │ Attrition │ Attrition % │ Active │ Avg Age  │
├──────────────────┬─────────────────┬────────────────┤
│ Department       │ Age Distribution│ Gender         │
│ Distribution     │                 │ Distribution   │
├──────────────────┴─────────────────┴────────────────┤
│ Education Distribution │ Age Band & Gender          │
└─────────────────────────────────────────────────────┘
```

------------------------------------------------------------------------

## 📌 Data Quality / Dashboard Improvement Recommendations

Before using the dashboard for executive decision-making, I would make
the following improvements:

### 1. Correct the Department Visual Title

Change:

> **Attrition by Department**

to:

> **Employee Distribution by Department**

unless the visual is redesigned to calculate department-level attrition.

### 2. Add True Department Attrition Rate

A better visual would compare:

``` text
Department
    ↓
Employee Count
    ↓
Attrition Count
    ↓
Attrition Rate
```

This avoids confusing a large department with a high-risk department.

### 3. Add Attrition Trend

Add monthly/quarterly attrition trends to identify whether turnover is:

-   Increasing
-   Decreasing
-   Seasonal
-   Stable

### 4. Add Attrition Drivers

Include job satisfaction, overtime, income, tenure, promotion history,
and business travel to identify potential reasons behind employee exits.

### 5. Add Drill-through

Create an employee-level drill-through page so HR users can investigate
individual employee segments without overcrowding the main dashboard.

------------------------------------------------------------------------

## 🚀 Business Impact

This dashboard can help HR teams:

-   Monitor overall workforce health
-   Identify high-risk employee segments
-   Prioritize retention initiatives
-   Understand workforce demographics
-   Support workforce planning
-   Identify departments requiring deeper analysis
-   Improve HR decision-making through data

The next step would be to combine **attrition rate + attrition drivers +
employee tenure + compensation + job satisfaction** to build a more
actionable employee-retention strategy.

------------------------------------------------------------------------

## 📂 Suggested GitHub Repository Structure

``` text
HR-Analytics-PowerBI/
│
├── README.md
├── Dashboard/
│   └── HR_Analytics_Dashboard.pbix
│
├── Data/
│   └── HR_Employee_Data.csv
│
├── Screenshots/
   └── HR Attrition Dashboard.PNG
```

------------------------------------------------------------------------

## 📸 Dashboard Preview

The dashboard provides an executive-level snapshot of workforce size,
attrition, demographics, education, department distribution, and
age/gender composition.

------------------------------------------------------------------------

## 👨‍💻 Project Skills Demonstrated

**Data Analytics \| HR Analytics \| Power BI \| DAX \| Power Query \|
Data Modeling \| KPI Development \| Data Visualization \| Business
Intelligence \| Workforce Analytics \| Attrition Analysis \| Business
Insights**

------------------------------------------------------------------------

## ⭐ Conclusion

The HR Analytics Dashboard demonstrates how Power BI can transform
employee data into actionable workforce intelligence.

The most important takeaway is that **overall attrition is 16.12%**,
while the workforce is heavily concentrated among **25--44-year-old
employees**, with **R&D representing 65.37% of the workforce** and a
**60% male / 40% female** workforce composition.

For a complete HR decision-support solution, the dashboard should be
extended from workforce description into **root-cause attrition analysis
and predictive retention analytics**.
