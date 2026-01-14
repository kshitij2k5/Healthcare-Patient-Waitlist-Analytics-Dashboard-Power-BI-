## 📊 **Project Title**

**Healthcare Patient Waitlist Analytics Dashboard (Power BI)**

---

## 📘 **README.md**

### 🏥 Project Overview

The **Healthcare Patient Waitlist Analytics Dashboard** is an interactive data visualization project designed to analyze, monitor, and compare patient waitlists across different case types, specialties, age groups, and time periods.
This dashboard helps healthcare administrators and decision-makers identify bottlenecks, trends, and priority areas to improve patient care delivery and reduce waiting times.

The dashboard is built with a strong focus on **clarity, usability, and actionable insights**, using KPIs, trend analysis, and drill-down visuals.

---

### 🎯 Objectives

* Track **total patient waitlists** over time
* Compare **current vs previous year** waitlists
* Analyze waitlists by **case type**, **specialty**, and **age group**
* Understand **long-term vs short-term waiting patterns**
* Enable **data-driven healthcare planning and optimization**

---

### 🗂️ Dataset Description

The dashboard uses healthcare waitlist data containing:

* Patient archive dates
* Case types (Outpatient, Day Case, Inpatient)
* Specialty names and specialty groups
* Patient age profiles
* Wait time bands (0–3 months, 3–6 months, …, 18+ months)

---

### 🧩 Key Features & Visuals

#### 1️⃣ **Total Wait List Comparison (KPI Cards)**

* Displays:

  * **Latest Month Wait List** (e.g., 709K)
  * **Previous Year Latest Month Wait List** (e.g., 640K)
* Helps in **year-over-year performance comparison**

---

#### 2️⃣ **Wait List Bifurcation by Case Type**

* Donut chart showing distribution across:

  * Outpatient
  * Day Case
  * Inpatient
* Includes:

  * Percentage contribution
  * Overall average wait value

📌 Insight: Quickly identifies which case type dominates the waitlist.

---

#### 3️⃣ **Key Indicators – Patient Wait List (Average / Median)**

* Toggle between:

  * **Average**
  * **Median**
* Prevents skewed interpretation caused by extreme values.

---

#### 4️⃣ **Wait List Analysis: Time Band vs Age Profile**

* Stacked bar chart combining:

  * Wait time bands (0–3 months to 18+ months)
  * Age profiles:

    * 0–15
    * 16–64
    * 65+
* Reveals how different age groups are impacted by long waiting periods.

---

#### 5️⃣ **Top 5 Wait Lists by Specialty**

* Ranked list of specialties such as:

  * Accident & Emergency
  * Paediatric Dermatology
  * Paediatric ENT
  * Paed Orthopaedic
  * Paed Cardiology

📌 Insight: Helps prioritize resource allocation to high-demand specialties.

---

#### 6️⃣ **Specialty Group Breakup (Drill-Through View)**

* Displays **Total Wait List (e.g., 68,807)** for a selected filter.
* Horizontal bar chart showing waitlist distribution across:

  * General
  * Bones
  * Urine
  * Eyes
  * ENT
  * Heart
  * Respiratory, Immune System, etc.

📌 Insight: Enables deep-dive analysis into specialty categories.

---

#### 7️⃣ **Monthly Trend Analysis**

* Line charts showing trends for:

  * **Day Case vs Inpatient**
  * **Outpatients**
* Time range:

  * 2018 to 2021

📌 Insight: Identifies seasonal spikes, growth patterns, and anomalies.

---

### 🎛️ Interactive Filters & Slicers

* **Archive Date Range Slider**
* **Case Type Dropdown**
* **Specialty Name Dropdown**

These filters dynamically update **all visuals** for real-time exploration.

---

### 🛠️ Tools & Technologies

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Healthcare Dataset (CSV / Excel / Database)**
* **Data Modeling & Relationships**
* **Custom Dark Theme UI**

---

### 📈 Key Insights Enabled

* Outpatients contribute the **largest share** of the waitlist
* Long waiting periods (18+ months) are significantly high
* Certain pediatric and emergency specialties are under high pressure
* Overall waitlists show an **upward trend over time**

---

### 🚀 Use Cases

* Hospital administration dashboards
* Healthcare policy analysis
* Operational efficiency monitoring
* Academic & portfolio projects in **Data Analytics / Power BI**

---

### 📂 Project Structure (Suggested)

```
Healthcare-Waitlist-Dashboard/
│
├── Data/
│   └── healthcare_waitlist_data.csv
│
├── Dashboard/
│   └── Healthcare_Waitlist_Dashboard.pbix
│
├── Screenshots/
│   └── dashboard_overview.png
│
└── README.md
```

---

### 🧠 Future Enhancements

* Add **predictive forecasting** for waitlists
* Include **hospital-wise comparison**
* Integrate **real-time data sources**
* Add patient outcome and discharge analytics

---

### 👤 Author

**Kshitij Sinha**
📊 Data Analytics | Power BI | SQL | Excel

---
