# 🏧 Wisabi Bank — ATM Transactions Analysis Dashboard | Power BI

An interactive 3-page Power BI dashboard analyzing ATM transaction data for Wisabi Bank across 5 Nigerian states — built as a guided learning project by following a YouTube tutorial.

---

## 📊 Dashboard Preview

### Home

### Overview — ATM Transactions Report

### Demography — Demographics Report

---

## ⚠️ Attribution

> This dashboard was built by following a YouTube tutorial as a hands-on learning exercise.
> **Original tutorial:** [Watch on YouTube](https://youtu.be/Lub16PueF-8)
> All credit for the project concept, dataset, and design goes to the original creator.
> This repository is shared for portfolio and learning purposes only.

---

## 📌 Project Overview

This project simulates a real-world data analytics engagement where Wisabi Bank — a Nigerian financial institution with branches in **Lagos, Kano, Rivers State, Enugu, and FCT Abuja** — needs insights into their ATM operations to improve customer experience and optimize performance.

The dashboard was built using a fact-dimension data model covering transactions throughout **2022**.

---

## 📄 Pages & Features

### 🏠 Home
A branded landing page with navigation to the Overview and Demography report pages.

### 📊 Overview — ATM Transactions Report
High-level KPIs and operational insights:
- **Total Transaction Amount** — 39bn
- **Customer Count** — 8,819
- **Total Transactions** — 2M
- **ATM Utilization Rate** — 12.9%
- Transaction Count Trend by Hour & Location (area chart — Lagos, Kano, Enugu, Rivers State, FCT)
- Average Duration vs Average Transaction Amount by State (animated scatter plot with timeline)
- Average Transaction Amount by State & Transaction Type (horizontal bar chart)
- Trend of Transaction Amount & Transaction Count by Month (dual-axis line chart)

### 👥 Demography — Demographics Report
Customer segmentation and behavioral analysis:
- Transaction Frequency by Age Group (bar chart — 7 age bands from 0-15 to 65+)
- Transaction flow by Type → Wisabi Status → Occupation (Sankey/flow chart)
- Transaction Count by Age Group & Type (stacked bar chart — Balance Inquiry, Deposit, Transfer, Withdrawal)
- Transaction Count by Type — Withdrawal dominates at 55.5% (donut chart)
- Average Duration by State & Transaction Type (stacked bar chart)

---

## 🛠️ Tools & Skills Used

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard development |
| **DAX** | KPI measures, utilization rate, averages, transaction type breakdowns |
| **Power Query (M)** | Data cleaning and transformation |
| **Data Modeling** | Star schema — Transactions fact table + Location, Customers, Transaction Type, Hour, Calendar dimensions |

---

## 💡 Key Insights

- **Lagos** leads all states in both transaction volume and average transaction amount
- **Withdrawal** is the most common transaction type, accounting for over 55% of all transactions
- The **16–35 age group** has the highest transaction frequency across all types
- ATM activity peaks between **9:00 AM and 15:00 PM** across all locations
- **ATM Utilization Rate of 12.9%** suggests significant room for operational improvement

---

## 📁 Repository Structure

```
wisabi-atm-dashboard/
├── README.md
├── WisabiATMDashboard.pbix
└── screenshots/
    ├── home.png
    ├── overview.png
    └── demography.png
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `WisabiATMDashboard.pbix` in Power BI Desktop
4. Navigate between pages using the Home, Overview, and Demography buttons

---

## 📚 What I Learned

- Building a **star schema** data model with multiple dimension tables
- Writing DAX measures for **utilization rate** and **average transaction duration**
- Using **animated scatter plots** to show trends over time
- Creating **Sankey-style flow charts** for demographic segmentation
- Designing a professional dark-themed dashboard layout

---