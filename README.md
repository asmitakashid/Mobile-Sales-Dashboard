# 📱 Mobile Sales Dashboard with Power BI

## 🔍 Project Overview

The **Mobile Sales Dashboard** is a beginner-friendly, step-by-step Power BI project designed to teach key Business Intelligence concepts through practical application. Using raw mobile sales Excel data, this project walks through the full ETL process, data modeling, DAX calculations, and the creation of an interactive dashboard.

Whether you're a Power BI beginner or someone looking to reinforce your data modeling and visualization skills, this project demonstrates best practices for building a professional-grade dashboard.

---

## 🎯 Screenshots
<img width="1310" height="735" alt="1" src="https://github.com/user-attachments/assets/325a483b-613c-4431-90cb-09b6d6a1c771" />
<img width="1305" height="732" alt="2" src="https://github.com/user-attachments/assets/0626e5e1-3ab3-4317-97bc-f8d480be2b2f" />
<img width="1312" height="737" alt="3" src="https://github.com/user-attachments/assets/ceae225a-1f94-4cf8-8e6a-33b02f80e11a" />


## 🎯 Key Features

### 🧪 ETL & Data Preparation
- Clean and transform messy sales data using **Power Query (M Language)**.
- Handle inconsistent data, missing values, and column standardization.
- Normalize dimension tables for better model performance.

### 📅 Custom Calendar Table
- Dynamic calendar created using Power Query.
- Supports complete **MTD/QTD/YTD** analytics without missing dates.
- Integrates public holidays and custom fiscal years (optional).

### 🔗 Relationship Modeling
- Connects **fact** (sales) and **dimension** (date, product, location) tables using a **star schema**.
- Enables efficient slicing and dicing of data.

### 📊 Advanced DAX Calculations
- **Cumulative Totals:** Automate running totals for sales metrics.
- **MTD / QTD / YTD Measures**
- **YoY & Same Period Last Year Analysis (SPLY)**
- Dynamic KPIs using `CALCULATE()`, `DATESYTD()`, `SAMEPERIODLASTYEAR()`, and other advanced DAX functions.

### 🖥️ Interactive Dashboard Design
- Fully interactive and user-friendly dashboard.
- Filters and slicers by:
  - Mobile Model
  - City
  - Payment Method
  - Date Range
- KPI Cards, Line Charts, Bar Graphs, and Tables.
- Clear color-coding and layout for quick insights.

### ☁️ Power BI Service Ready
- Optimized for publishing and sharing on Power BI Service.
- Includes:
  - Bookmark navigation
  - Drill-through pages
  - Report tooltips

---

## 📁 Folder Structure

```bash
📦Mobile-Sales-Dashboard/
├── 📂 dashboard/     # Power BI .pbix file
├── 📂 dataset/       # Raw Excel data files
├── 📂 screenshot/    # PNG/JPG screenshots of the dashboard
└── README.md         # Project overview and instructions

