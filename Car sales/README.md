# 🚗 Car Sales Analysis Dashboard — Power BI

An interactive multi-page Power BI dashboard analyzing car sales performance across sellers, manufacturers, models, and regions in the United States.

---

## 📊 Dashboard Preview

### Home Page
![Home](screenshots/home.png)

### Manufacturer Page
![Manufacturer](screenshots/manufacturer.png)

### Car Model Page
![Car Model](screenshots/car_model.png)

---

## 📌 Project Overview

This dashboard was built to analyze used car sales data and uncover insights around revenue trends, top-performing models, seller performance, and geographic distribution of sales across the US.

---

## 📄 Pages & Features

### 🏠 Home
High-level KPIs and overall sales performance:
- **Total Sales Revenue** — 4M
- **Total Cars Sold** — 3K
- **Average Selling Price** — 1.2K
- **Number of Models** — 186
- Sales Revenue trend by Quarter and Month (line chart)
- Total Cars Sold by Model (horizontal bar chart)
- Total Cars Sold by Seller (treemap)
- Cars Sold by Body Type (donut chart)
- Cars Sold by Transmission Type (donut chart)

### 🏭 Manufacturer
Breakdown of sales by manufacturer and geography:
- Matrix table — Models vs Manufacturers with Total Sales, Total Sales Revenue, and % Above MMR Price
- US Sales Map — geographic distribution of car sales by state
- KPI Cards — Total Sales by Target and Total Revenue by Target

### 🚘 Car Model
Deep-dive into individual car make performance:
- Summary table — Make, Total Cars Sold, Total Sales Revenue, Average Selling Price
- Scatter plot — Average MMR vs Average Selling Price with Price Deviation by Make
- Decomposition Tree — drill-down from Total Cars Sold → Make → Model → Year

### 🔍 Tooltip
Custom tooltip page showing a quick-glance table of Total Sales and Total Revenue by Make, used as a hover tooltip across visuals.

---

## 🛠️ Tools & Skills Used

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard development |
| **DAX** | Calculated measures (KPIs, % Above MMR, averages) |
| **Power Query (M)** | Data cleaning and transformation |
| **Data Modeling** | Relationships between tables |

---

## 💡 Key Insights

- **Ford, Honda, and Toyota** are the top-selling makes by volume
- **Lexus and BMW** have the highest average selling prices
- The majority of cars sold are **Sedans** and **SUVs**
- **Automatic transmission** dominates sales over manual
- Sales peaked in **Q1** and saw a significant dip mid-year

---

## 📁 Repository Structure

```
car-sales-dashboard/
├── README.md
├── CarSalesDashboard.pbix
└── screenshots/
    ├── home.png
    ├── manufacturer.png
    ├── car_model.png
    └── tooltip.png
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `CarSalesDashboard.pbix` in Power BI Desktop
4. Explore the interactive visuals and slicers

---

## 👤 Author

**[Your Name]**  
[LinkedIn Profile](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)
