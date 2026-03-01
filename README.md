Here is your **GitHub README.md** version formatted cleanly in Markdown format.
(Structured, professional, and optimized for GitHub presentation.)

---

# 📊 COVID-19 Analytical Dashboard – Power BI Project

## 📌 Project Overview

This project presents a comprehensive, interactive, and data-driven **COVID-19 Analytical Dashboard** developed using **Power BI**.

The dashboard integrates nationwide case data, vaccination progress, and testing statistics into a unified analytical platform that enables dynamic monitoring of the pandemic across Indian states.

The primary goal of this project is not just visualization, but structured analytical transformation of raw healthcare datasets into actionable insights. The dashboard supports:

* Comparative analysis
* Trend identification
* Statistical interpretation
* Policy-level evaluation

---

## 🎯 Project Objectives

* Analyze COVID-19 case trends (Daily, Weekly, Monthly)
* Monitor cumulative confirmed, recovered, deaths, and active cases
* Evaluate vaccination progress across states and age groups
* Compare pandemic behavior before and after vaccination rollout
* Assess healthcare performance using Recovery Rate and CFR
* Analyze testing efficiency using Positivity Rate and Testing Rate
* Study correlation between testing intensity and infection detection
* Build an interactive decision-support dashboard using slicers and drill-down features

---

## 🗂️ Data Model Overview

The dashboard is built on cleaned and structured datasets integrated into Power BI.

### 🔹 Key Data Attributes

* Date
* State
* Confirmed Cases
* Deaths
* Recovered (Cured)
* Daily New Cases
* Total Samples Tested
* Positive Cases
* Total Doses Administered
* First Dose
* Second Dose
* Individuals Vaccinated
* Population
* Age Group

All analytical measures were created using **DAX (Data Analysis Expressions)**.

Dynamic cumulative calculations were implemented using:

```DAX
MAX(Date)
```

This ensures KPI cards always reflect the most recent reporting date based on applied filters.

---

# 📈 COVID-19 Case Summary Analysis

## 1️⃣ Key KPIs

| Metric                | Value       |
| --------------------- | ----------- |
| Total Confirmed Cases | ~32 Million |
| Total Deaths          | ~429K       |
| Total Recovered       | ~31 Million |
| Active Cases          | ~386K       |
| Daily New Cases       | ~38K        |
| Recovery Rate         | ~97.45%     |

### 🔎 Key Insights

* High recovery rate reflects improved healthcare capacity.
* Active cases significantly lower than total confirmed → stabilization phase.
* Multiple infection waves identified during analysis period.

---

# 🧪 Testing Analysis

## 📌 National Testing Summary

* **Total Tests Conducted:** 524+ Million
* **National Positivity Rate:** ~1.19%

A lower positivity rate suggests adequate testing relative to spread.

---

## 📊 State-wise Positivity Rate Comparison

### 🔴 High Positivity States

* Madhya Pradesh – 5.23%
* Tripura – 4.93%
* Haryana – 4.41%
* Maharashtra – 3.28%
* Kerala – 2.85%

### 🟢 Low Positivity States

* Mizoram – 0.10%
* Lakshadweep – 0.10%
* Uttar Pradesh – 0.17%

### 💡 Analytical Insight

* High Positivity → Possible concentrated infection or under-testing
* Low Positivity → Wider testing coverage & better control

---

## 📉 Testing Rate vs Positivity Rate (Scatter Analysis)

**Scatter Plot Components:**

* X-Axis → Testing Rate %
* Y-Axis → Positivity Rate %
* Bubble Size → Confirmed Cases
* Legend → State

```
Testing Rate = Total Samples ÷ Population
```

### 📌 Interpretation Matrix

| Scenario                       | Meaning                |
| ------------------------------ | ---------------------- |
| High Testing + Low Positivity  | Effective Surveillance |
| Low Testing + High Positivity  | Hidden Spread Risk     |
| High Testing + High Positivity | Severe Outbreak Phase  |

This visualization supports policy-based testing allocation decisions.

---

# 📊 Advanced Statistical Analysis

## 📌 Case Fatality Rate (CFR %)

```
CFR = Deaths ÷ Confirmed Cases
```

### 🔴 High CFR States

* Punjab – 2.72%
* Uttarakhand – 2.15%
* Maharashtra – 2.11%

### 🟢 Low CFR States

* Mizoram – 0.37%
* Kerala – 0.50%
* Telangana – 0.59%

### 📌 Interpretation

* Higher CFR → Healthcare strain or vulnerable population
* Lower CFR → Better medical intervention and case management

---

# 💉 Pre vs Post Vaccination Trend Analysis

📅 Vaccination rollout began on **16 January 2021**

Data segmented into:

* Pre-Vaccination Phase
* Post-Vaccination Phase

### 📌 Observations

* Post-vaccination phase initially saw a surge (Second Wave)
* Long-term trend shows stabilization and decline in active cases

### ✅ Conclusion

Vaccination significantly contributed to reduced severity and improved recovery over time.

---

# 💉 Vaccination Progress Analysis

## 📌 Key Vaccination Metrics

| Metric                   | Value        |
| ------------------------ | ------------ |
| Total Doses Administered | ~513 Million |
| Vaccination Coverage     | ~48.84%      |
| First Dose               | ~400 Million |
| Second Dose              | ~113 Million |
| Individuals Vaccinated   | ~251 Million |

### 📊 Age Group Distribution

* 18–44 Years → Largest vaccinated population (workforce size)
* 45–60 Years
* 60+ Years → Prioritized early due to vulnerability

Balanced distribution reflects phased rollout strategy.

---

# 📈 Trend Analysis Visualizations

The dashboard includes:

* Confirmed, Deaths & Recovered Line Chart
* Daily Case Trend Analysis
* Weekly & Monthly Aggregation
* Cumulative Vaccination Trend
* Pre vs Post Vaccination Comparative Graph

### 🔎 Insights Identified

* First wave
* Second wave peak
* Post-vaccination stabilization phase

---

# 🎛️ Interactive Dashboard Features

The dashboard incorporates:

* State Slicer
* Year Slicer
* Month Slicer

These features enhance exploratory analysis and user-driven insights.

---

# 🛠️ Tools & Technologies Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling Techniques
* Time Intelligence Functions
* Data Cleaning & Transformation

---

# 🏁 Conclusion

The COVID-19 Analytical Dashboard successfully integrates multi-dimensional healthcare data into a single interactive reporting platform.

### 🎯 Key Outcomes

* Identified infection waves
* Evaluated vaccination impact
* Measured healthcare performance
* Compared state-wise outbreak intensity
* Analyzed testing efficiency
* Demonstrated statistical reasoning
