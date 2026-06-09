# 🍫 Awesome Chocolates — Executive Sales Analytics Dashboard

> **Power BI | Data Modeling | DAX | Executive Visualization**  
> **Author:** Awwal | **Academy:** HayMedics Academy | **Status:** Completed ✅

---

## 📌 Project Overview

This is a **comprehensive executive-level sales analytics dashboard** built for **Awesome Chocolates** — a chocolate company with products, salespeople, and shipments across multiple regions.

The dashboard is designed the way a **real business analyst** would present it to senior leadership — clean, interactive, and packed with actionable insights.

---

## 🏗️ What Was Built

### 1. 🗂️ Semantic Data Modeling
- Designed a **Star Schema** with separate fact and dimension tables
- Built for scalability, performance, and clean relationships
- Dimension tables: Products, Salespeople, Geography, Calendar
- Fact table: Sales transactions

### 2. 🔧 Data Transformation (Power Query)
- Cleaned and prepared raw data using **Power Query**
- Created a **Calendar Table** to enable time intelligence calculations
- Handled data types, nulls, and column formatting

### 3. 📐 DAX Calculations
Custom measures created:

| Measure | Purpose |
|--------|---------|
| Total Sales | Revenue across all products |
| Total Cost | Cost of goods sold |
| Total Profit | Sales minus Cost |
| Profit % | Profitability ratio |
| Total Boxes | Volume of boxes shipped |
| LBS (Low Box Shipments) | Tracks inefficient small shipments |
| MoM Sales Growth | Month-over-month % change |

### 4. 📊 Executive Visualizations
- **KPI Cards** — instant snapshot of key numbers
- **Trend Charts** — sales performance over time
- **Histograms** — distribution analysis
- **Dynamic Tooltips** — hover to see geographic distribution
- **Conditional Formatting** — highlights growth vs. decline automatically

---

## ✨ Key Features

- 📅 **Month-over-Month Analysis** — track whether sales are growing or falling
- 📦 **LBS Tracking** — identify and reduce low-efficiency shipments
- 🌍 **Geographic Distribution** — see where sales come from via dynamic tooltips
- 🔄 **Field Parameters** — toggle between metrics without rebuilding visuals
- 🔖 **Bookmarks & Selection Panes** — seamless, app-like navigation experience

---

## 🛠️ Tools & Skills Used

- **Microsoft Power BI Desktop**
- **Power Query** (ETL / data transformation)
- **DAX** (Data Analysis Expressions)
- **Star Schema** data modeling
- **Data Analytics · Data Science · Data Loading**
---

## 📁 Repository Structure

```
📂 awesome-chocolates-powerbi/
├── 1st_Power_BI_Project_Awwal.pbix   ← Power BI Dashboard file
├── README.md                          ← Project documentation
└── dashboard.png                      ← Dashboard screenshot (add this)
```

---

## 🚀 How to Open

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Download the `.pbix` file from this repo
3. Open Power BI → **File → Open** → select the file
4. Explore the full interactive dashboard!

---

## 💡 Business Value

This dashboard helps chocolate company executives:
- Instantly see if monthly sales targets are being met
- Identify underperforming salespeople or regions
- Reduce costs by tracking low-box shipments (LBS)
- Make faster, data-driven decisions with clean visuals

---

## 👤 About Me

I'm **Awal**, a **Full Stack Data Scientist and AI Engineer**, building real-world projects to become job-ready.  


---

## 📅 Completed

December 2025

---

*⭐ If this project helped or inspired you, please star this repository!*
