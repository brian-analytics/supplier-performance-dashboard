# Supplier Performance Dashboard  
### Procurement KPI Analytics with Power BI

**Objective:**  
Evaluate supplier risk, operational performance, and financial impact using
procurement KPIs to support data-driven sourcing and supplier management decisions.

---

## Project Overview

This project analyzes procurement operations using real-world-inspired purchase
order data. The goal is to move beyond descriptive reporting and provide **actionable
insights** that help procurement teams:

- Identify high-risk suppliers
- Diagnose operational bottlenecks
- Prioritize suppliers with the greatest financial impact
- Balance reliability against cost savings

The analysis was implemented in **Power BI**, with calculated KPIs built using **DAX**
and structured data preparation in **Excel**.

---

## Dashboard Structure

The dashboard is organized into **three analytical layers**, each answering a
different business question.

---

## 1. Supplier Overview & Risk–Value Trade-off

![Supplier Overview](../screenshots/page1_supplier_overview.png)

**Key question:**  
> Which suppliers are strategic assets, and which pose operational or financial risk?

### Highlights
- A **Supplier Reliability Score** combines delivery performance, quality, and compliance.
- A **quadrant scatter plot** maps reliability against total cost savings.
- Suppliers are segmented into:
  - Strategic Partners
  - Value Opportunities
  - At-Risk Suppliers
  - Reliable but Low Impact

**Outcome:**  
Procurement leaders can immediately identify which suppliers to strengthen,
renegotiate, or closely monitor.

---

## 2. Operational Diagnostics

![Operational Diagnostics](../screenshots/page2_operational_diagnostics.png)

**Key question:**  
> Where are operational inefficiencies originating?

### Metrics Analyzed
- On-Time Delivery %
- Average Delivery Delay (Days)
- Defect Rate
- Compliance Rate

### Insights
- Highlights suppliers driving delays or quality issues
- Reveals trade-offs between speed, quality, and compliance
- Supports targeted corrective actions rather than broad supplier penalties

**Outcome:**  
Enables focused operational improvements and supplier performance management.

---

## 3. Financial Impact & Action Prioritization

![Financial Impact](../screenshots/page3_financial_impact.png)

**Key question:**  
> Where should procurement focus to maximize financial returns?

### Features
- Total and unit cost savings by supplier
- Reliability-adjusted financial prioritization
- Integrated risk indicators alongside savings metrics

**Outcome:**  
Supports smarter sourcing decisions by aligning **cost savings** with
**supplier reliability**.

---

## Key KPIs Used

- Supplier Reliability Score (weighted index)
- On-Time Delivery %
- Defect Rate
- Compliance Score
- Total Cost Savings
- Unit Cost Savings
- Average Delivery Delay (Days)

---

## Tools & Technologies

- **Power BI** – data modeling, visualization, and analytics
- **DAX** – KPI calculations and scoring logic
- **Excel** – data cleaning and preparation
- **GitHub Pages** – project documentation and presentation

---

## Data Flow

- Excel Dataset
     ↓
- Power BI (Data Model & DAX Measures)
     ↓
- Interactive Dashboard
     ↓
- GitHub Pages (Case Study & Documentation)
---

## Repository

📂 **GitHub Repository:**  
[Supplier Performance Dashboard](https://github.com/brian-analytics/supplier-performance-dashboard)

---

## Conclusion

This project demonstrates how procurement data can be transformed into a
decision-support tool that balances **risk, performance, and financial value**.
The approach mirrors real-world business intelligence workflows used in
procurement, supply chain, and operations analytics.

---


