# 📱 Mobile Phone Market Analysis Dashboard | Power BI

An interactive multi-page Power BI dashboard analyzing the global smartphone market — covering 980 models across 46 brands, with insights into pricing, hardware specifications, OS distribution, and performance benchmarks.

---

## 📊 Dashboard Preview

### Home

### Performance Specifications

---

## 📌 Project Overview

This dashboard was independently designed and built to explore the smartphone market landscape. It allows users to compare brands, analyze hardware trends, and drill into individual model specifications — making it useful for anyone evaluating devices or studying the competitive mobile market.

---

## 📄 Pages & Features

### 🏠 Home
Market-level overview of the smartphone landscape:
- **Number of Brands** — 46
- **Number of Models** — 980
- Brands by OS — Android dominates at 92.76%, iOS at 4.69% (donut chart)
- Screen Resolution vs Battery Capacity — relationship between display quality and battery size (scatter plot)
- Total Price by Brand Name — comparative bar chart across all 46 brands (Samsung and Apple lead)
- Models by Brand — Xiaomi (134), Samsung (132), Vivo (111), Realme (97), Oppo (88) top the list
- Combined metrics card — Fast Charging, Rating, and Processor Speed summary

### ⚙️ Performance Specifications
Detailed hardware and spec analysis per model:
- Brand & Model selector — scrollable list for drilling into specific devices
- Average Processor Speed by Processor Brand (combo bar + line chart)
  - Processor brands covered: Bionic, Dimensity, Snapdragon, Kirin, Exynos, Google, Helio, and more
- KPI cards for the selected model/brand:
  - Battery Capacity, Rear Cameras, Processor Speed, Operating System
  - Price, Screen Size, RAM Capacity, Storage Range
  - Processor Brand, Refresh Rate, Rating, Number of Cores

---

## 🛠️ Tools & Skills Used

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard design and development |
| **DAX** | Calculated measures for KPIs, averages, and aggregations |
| **Power Query (M)** | Data cleaning, column transformation, and categorization |
| **Data Modeling** | Structured model to support cross-filtering across specs |

---

## 💡 Key Insights

- **Android overwhelmingly dominates** the smartphone market at nearly 93% of all models
- **Xiaomi and Samsung** offer the widest model variety among all brands
- **Apple's Bionic chip** leads all processor brands in average speed (2.32 GHz)
- There is a clear correlation between higher screen resolution and increased battery capacity
- **Samsung and Apple** generate the highest total price volume across their model ranges

---

## 📁 Repository Structure

```
mobile-phone-dashboard/
├── README.md
├── MobilePhoneDashboard.pbix
└── screenshots/
    ├── home.png
    └── performance_specs.png
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `MobilePhoneDashboard.pbix` in Power BI Desktop
4. Use the Brand & Model selector on the Performance page to explore individual device specs

---

