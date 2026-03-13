# 🎬 ORION — Movie Box Office Analysis Dashboard | Power BI

An interactive multi-page Power BI dashboard analyzing global movie box office performance across genres, directors, countries, and certificate ratings — spanning data from 1921 to 2004.

---

## 📊 Dashboard Preview

### Overview Dashboard

### Director Analysis

### Genre and Country Insights

---

## 📌 Project Overview

The **ORION** dashboard was built to explore the movie industry's financial performance and Oscar recognition trends. It covers box office revenue by genre, director rankings by nominations and wins, country-level breakdowns, and historical growth trends — all filterable by date, country, and genre.

A standout feature is the built-in **Light/Dark mode toggle**, providing a polished, user-friendly viewing experience.

---

## 📄 Pages & Features

### 🏠 Overview Dashboard
High-level KPIs and box office performance:
- **Total Box Office Revenue** — 106.73bn+
- **Profit Margin**
- **Total Movies Count** — 197
- Total Box Office by Genre & Certificate (stacked bar chart, switchable by Country / Genre / Director)
- Box Office All by Year — historical trend from 1920 to 2000s (with Oscar Winners toggle)
- **YoY Box Office Growth** — year-over-year growth rate
- Oscar Winners by Certificate (donut chart)

### 🎥 Director Analysis
In-depth director performance metrics:
- Movies by Runtime Categories — Short / Medium / Long (donut chart)
- Oscar Winner Movies by Runtime Categories (donut chart)
- Director ranking table — Nominations, Oscar Wins, Average Nominations per film
  - Top directors: Steven Spielberg (101 nominations, 30 wins), David Lean, James Cameron, Peter Jackson, Francis Ford Coppola, Martin Scorsese
- Top N Directors by Box Office Value (treemap — switchable Top 10 / Top 20)

### 🌍 Genre and Country Insights
Geographic and genre-level revenue breakdown:
- Matrix table — Country vs Genre Box Office Revenue (Action, Adventure, Animation, Biography, Comedy, and more)
- Total Box Office by Certificate rating (donut chart — ratings: 12, 15, 18, PG, U)
- Filterable by country (Australia, Brazil, Canada, China, France, Germany, Hong Kong, Italy, Japan, UK, US, and more)
- Runtime category filter (Long / Medium / Short)

### 🔍 Box Office Tooltip
Custom hover tooltip showing Top Movies by Total Box Office, including:
- Avatar — 2.79bn
- Titanic — 2.19bn
- Star Wars: The Force Awakens — 2.07bn
- Jurassic World, The Avengers, Furious 7, and more

---

## ✨ Special Features

| Feature | Description |
|---------|-------------|
| **Light / Dark Mode Toggle** | Switch between themes using the bookmark button on each page |
| **Cross-page Navigation** | Navigation buttons link Overview, Director Analysis, and Genre & Country pages |
| **Custom Tooltip** | Hover tooltip shows top-grossing movies by box office revenue |
| **Top N Filter** | Director treemap switches between Top 10 and Top 20 dynamically |
| **Date Range Slicer** | Filter all visuals by release date range (1921–2004) |

---

## 🛠️ Tools & Skills Used

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard development |
| **DAX** | KPI measures, YoY growth, Top N logic, Oscar win calculations |
| **Power Query (M)** | Data cleaning and transformation |
| **Bookmarks** | Light/Dark mode toggle and page navigation |
| **Data Modeling** | Relationships across movies, directors, genres, and countries |

---

## 💡 Key Insights

- **Science Fiction** generates the highest total box office revenue across all genres
- **Steven Spielberg** leads all directors with 101 nominations and 30 Oscar wins
- **Long runtime** films dominate Oscar wins compared to short and medium films
- **The United States** is by far the largest contributor to global box office revenue
- **Avatar** and **Titanic** are the top two highest-grossing individual films in the dataset
- Box office revenues grew dramatically from the **1970s onward**, with a peak in the early 2000s

---

## 📁 Repository Structure

```
orion-movie-dashboard/
├── README.md
├── OrionMovieDashboard.pbix
└── screenshots/
    ├── overview.png
    ├── director_analysis.png
    ├── genre_country.png
    └── tooltip.png
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `OrionMovieDashboard.pbix` in Power BI Desktop
4. Use the **Light/Dark mode toggle** and navigation buttons to explore pages
5. Apply slicers (Date, Country, Genre) to filter all visuals interactively


