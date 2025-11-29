# NY-Loan-Lending-Analysis

**Author:** Ishita Arora  
**Tools Used:** Power BI, Power Query, DAX, Excel, Dimensional Modelling  
**Project Type:** Data Analysis / BI Dashboard  
**Dataset:** HMDA (Home Mortgage Disclosure Act) – 5 consecutive years (New York region)

---

## 📖 Project Description

This project is an interview assignment where I analyzed real-world, messy banking records to derive actionable insights. Using the HMDA public dataset, I pulled loan application data for five consecutive years, cleaned and modeled it, and created relationships between more than 20 tables.

The final output is an interactive Power BI dashboard highlighting trends in loan approvals, rejections, lenders, borrowing patterns, and risk profiles across New York.

---

## 🗂 Project Overview

| Area | Details |
|------|---------|
| **Source Dataset** | HMDA Open Public Data |
| **Years Covered** | 2018–2022 (5 consecutive years) |
| **Total Raw Files** | 5 datasets → expanded to 20+ tables after modelling |
| **Objective** | Understand loan provider vs loan taker patterns, approval trends, risk indicators & demographic distribution |
| **Tools Used** | Power BI, Power Query, DAX, Excel, Dimensional Modelling |

---

## 📊 Dataset Overview

- **Source:** HMDA loan application data (2020–2024)  
- **Volume:** ~2 million applications from New York  
- **Coverage:** 1,633 unique applicants across financial institutions  

---

## 🏗 Technical Architecture

- Star schema with **fact table** + dimensional models  
- **Power Query** for data cleaning & transformation  
- **DAX measures** for comprehensive KPI calculation  

---

## 🔍 Challenges

Real-world banking data is messy. This project involved working with:  

- Missing values  
- Inconsistent formats  
- Duplicates  
- Irrelevant/noisy columns  
- Non-standard labels  

This gave me hands-on experience in practical data wrangling and cleaning, beyond textbook scenarios.

---

## 🧭 Approach & Workflow

### 1️⃣ Data Cleaning
Performed in **Power Query**:

- Removed duplicates and null-heavy columns  
- Standardized categorical fields  
- Normalized values (credit score range, loan amount band, etc.)  
- Split, merged, and formatted columns for readability

### 2️⃣ Dimensional Modelling & Relationships

- Used **Star Schema** methodology to break down raw files into **facts** and **dimensions**  
- Established relationships across 20+ tables for optimized analysis and reduced redundancy

### 3️⃣ Dashboard & Insights

The final Power BI dashboard highlights key lending trends across New York. Main KPIs include:

- ✅ **Approved applications**  
- ❌ **Denied applications**  
- 📊 **Approval rate**  
- 📉 **Denial rate**  
- 👥 **Total applicants**



> Note: For those interested in detailed calculations, DAX measures, or deeper analysis, feel free to reach me at [aroraishita596@gmail.com](mailto:aroraishita596@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/ishita-arora-51616b1b3/).

---

## ⚠️ Disclaimer

This repository presents the **main insights** derived from the HMDA dataset. The full analysis, including all dashboards, tables, and transformation steps, is showcased in the accompanying Power BI report / PPT. The README summarizes key trends and KPIs for quick reference.

---

## 📁 Repository Structure

NY-Loan-Lending-Analysis/
│

├── datasets/ --> Contains all 5 raw HMDA files

│ └── *.csv

│

├── data-modelling/

│ ├── data_model.png --> Final Power BI relationship view

│ └── power_query_steps.png --> Cleaning & transformation steps screenshot

│
├── dashboard/

│ └── dashboard.png --> Final Power BI report screenshot

│

└── README.md


---

## 🌟 Key Takeaways

- Real data is never clean . **cleaning and modelling** are crucial for reliable analysis.  
- **Dimensional modelling** improves clarity, performance, and analysis quality.  
- **DAX measures** bring insights to life beyond charts.  
- A dashboard is **not just visualization**; it’s a tool to make **data-driven decisions**.


