# Data Jobs Dashboard w/ Power BI

![Dashboard Page 1](/Images/Project1.png)
## Introduction

This dashboard was created for **Job Seekers, Job Transitioners, and Job Swappers** to solve a common problem: information about the data job market is scattered and hard to grasp. Using a *real-world dataset of 2024 data science job postings* (including titles, salaries, and locations), this project provides a single, easy-to-use interface to explore market trends and compensation.

## Skills Showcased

- **Data Transofrmation (ETL) with Power Query:** Cleaned, shaped, and prepared the raw data for analysis by handling blanks, changing data types, and creating new columns.

## 🚀 Key Features & Functionality

### 1. Dynamic KPIs (Core Metrics)
The dashboard tracks high-level metrics using custom DAX measures to provide immediate business context:
* **Total Job Postings:** Live count of all available data points in the set.
* **Median Salary:** Calculated to provide a more accurate benchmark than a standard average (reducing outlier bias).
* **Experience Distribution:** Visual breakdown of the workforce from Entry-level to Executive.

### 2. Interactive User Controls
The report is built for "self-service" exploration through:
* **Advanced Slicers:** Filter the entire dataset by **Job Title**, **Experience Level**, and **Company Size**.
* **Global Filters:** Toggle views between different **Employment Types** (Full-time, Contract, Freelance).

### 3. Deep-Dive Navigation
* **Drill-Through Pages:** Users can select a specific job title to be redirected to a detailed "Role Deep-Dive" page.
* **Bookmarks & Reset Buttons:** One-click navigation to toggle between "High-Level Summary" and "Detailed Data" views.
* **Tooltips:** Hover over charts to see hidden data points, such as specific currency conversions or remote-work percentages.

---

## 🛠️ Technical Implementation

### Data Modeling & Processing
* **Implicit & Explicit Measures:** Utilized for automated sum/count functions and complex logic.
* **Data Cleaning:** Performed via Power Query to standardize job titles, handle missing values, and convert global currencies into a single reporting currency.
* **Visual Selection:** Used clustered bar charts for salary comparisons and donut charts for remote-ratio distribution.

---

## 📈 Business Insights
This dashboard answers critical business questions:
1. **Competitive Pay:** What is the 75th percentile salary for a Data Scientist in a Mid-sized company?
2. **Geographic Strategy:** Which regions offer the highest pay-to-experience ratio for remote work?
3. **Hiring Trends:** Which job titles have seen the highest growth in postings over the last 24 months?

---

## 💻 Tech Stack
* **Tool:** Power BI / Tableau
* **Data Language:** DAX & Power Query (M)
* **Dataset:** Global Salary & Job Postings (CSV/Excel)

---

## Dashboard Overview

### Page 1: High-level Market View

![Dashboard Page 1](/Images/Project1.png)

This is your mission control for the data job market. It showcases key KPIs like total job count, median salaries, and top job titles to give you a quick understanding of what's happening in the job market at a glance.

### Page 2: Job Title Drill Through

![Dashboard Page 1](/Images/Project1_2.png)

This is the deep-dive page. From the main dashboard, you can drill through to this view to get specific details for a single job title, including salary ranges, work-from-home stats, top hiring platforms, and a global map of job locations.

---

## Conclusion

THis dashboard showcases how Power BI can transform raw job posting data into a powerful tool for career analysis. It allows users to slice, filter, and drill through data to make informed decisions about their career paths.