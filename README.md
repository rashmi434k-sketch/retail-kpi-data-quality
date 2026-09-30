# 📊 Retail KPI Governance & Data Quality Framework

## 🚀 Project Overview

This project focuses on building a reliable foundation for retail analytics by defining business KPIs clearly and validating the quality of the underlying data.

The project converts business requirements into:

- Standardized KPI definitions
- Data-quality rules
- Automated validation checks
- Data-quality thresholds
- Ownership and escalation procedures

The objective is to make sure that analytical reports and dashboards are based on data that is **consistent, complete, valid, and trustworthy**.

---

## 🎯 Business Objective

Retail organizations use metrics such as sales, orders, discounts, refunds, and average order value to monitor business performance.

However, inconsistent KPI definitions or poor-quality source data can lead to incorrect conclusions.

This project addresses that problem by establishing a structured framework for:

> **Define → Validate → Monitor → Escalate → Report**

---

## 👩‍💼 Decision Owner

**Primary Decision Owner:** Retail Operations Manager

### Key Stakeholders

- Finance Team
- Pricing Team
- Operations Team
- Data Engineering / Data Pipeline Team

---

# 📈 KPI Framework

The project defines eight core retail KPIs.

| KPI | Business Definition |
|---|---|
| Total Orders | Number of distinct valid orders |
| Gross Order Value | Total value before discounts |
| Net Sales | Sales value after applicable discounts |
| Units Sold | Total quantity of valid units |
| Average Order Value | Net sales divided by realized orders |
| Average Discount | Weighted average discount applied |
| Paid Order Rate | Percentage of orders successfully paid |
| Refund Rate | Percentage of orders that were refunded |

Each KPI includes:

- Business definition
- Calculation formula
- Data grain
- Filters
- Business rules
- KPI owner
- Refresh frequency

---

# 🔎 Data Quality Framework

The dataset is evaluated using multiple quality dimensions.

### 1. Completeness

Determines whether important fields contain missing values.

Examples:

```text
Order ID
Order Date
City
Quantity
Payment Status
