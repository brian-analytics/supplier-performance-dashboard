# Supplier Performance Dashboard  
### Procurement KPI Analytics | Power BI

This repository contains a **Power BI–driven supplier performance dashboard** designed to evaluate procurement operations across **risk, reliability, and financial impact** dimensions.

The project simulates a real-world procurement analytics workflow, from data preparation to executive-ready insights.

---

## 🔍 Project Overview

The dashboard analyzes supplier performance using key procurement KPIs:

- Supplier Reliability Score (weighted composite)
- On-Time Delivery %
- Defect Rate
- Compliance Rate
- Total and Unit Cost Savings

The goal is to enable **data-backed supplier prioritization** and **risk-aware sourcing decisions**.

---

## 📊 Dashboard Views

### 1. Supplier Overview & Risk–Value Trade-off
Identifies strategic suppliers by balancing reliability and financial contribution using quadrant analysis.

### 2. Operational Diagnostics
Breaks down delivery delays, defects, and compliance issues to uncover performance drivers.

### 3. Financial Impact & Action Prioritization
Connects supplier performance to cost savings and highlights where intervention yields the highest return.

👉 Full visual walkthrough available via **GitHub Pages**:  
**https://github.com/brian-analytics/supplier-performance-dashboard/**

---

## 🧠 Analytical Highlights

- Weighted reliability index using DAX
- Risk classification logic (Low / Medium / High)
- Locked quadrant thresholds for consistency
- Conditional formatting for rapid visual interpretation
- Drill-through–ready table structure

---

## 🛠 Tools Used

- **Power BI** (DAX, data modeling, visual analytics)
- **Python / Pandas** (raw data audit, data quality assessment, KPI modeling)
- **Jupyter Notebooks** (step-by-step reproducible analysis)
- **Microsoft Excel / CSV** (data storage & exports)
- **GitHub Pages** (documentation & presentation)

---

## 📁 Repository Structure
```text
├── data/
│   └── Raw/archive (2).zip
├── docs/
│   ├── index.md                        # GitHub Pages site
│   └── data_quality_issue_register.csv # Data quality issue register & decisions
├── images/
│   ├── supplier-overview.png
│   ├── operational-diagnostics.png
│   └── action-prioritization.png
├── outputs/
│   ├── audit/                          # Missingness & data validation audits
│   ├── kpi/                            # KPI summaries, quarterly trends & scorecard
│   └── procurement_data_cleaned.csv    # Cleaned procurement dataset
├── 01_raw_data_audit.ipynb             # Data quality audit notebook
├── 02_kpi_analysis.ipynb               # KPI calculation & scorecard notebook
├── Cleaned_Procurement_KPI_Dataset.xlsx
├── Procurement KPI Analysis Dataset.csv
├── Supplier Performance Dashboard.pbix  # Power BI dashboard
└── README.md
```

---

## 📌 Notes

- The dataset is synthetic but modeled on realistic procurement scenarios.
- Screenshots represent finalized dashboard views.
- Includes the full Power BI `.pbix` dashboard model and end-to-end Python audit pipelines.

---

👤 **Author**  
Brian — Data Analytics & Procurement Intelligence  

This project is intended for **portfolio demonstration**, technical interviews, and applied analytics discussion.

