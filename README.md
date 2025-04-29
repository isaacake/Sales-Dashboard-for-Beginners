#  📊 Sales-Dashboard-for-Beginners
Welcome to the Sales Performance Analysis Dashboard! This project provides a comprehensive visualization and analysis of regional sales data across various metrics including profit, targets, customer count, and satisfaction scores.

---

## 📖 TABLE OF CONTENT

- [Visual Preview](#visual-Preview)
- [Project Structure](#project-Structure)
- [Data Source](#data-Source)
- [Dataset Description](#dataset-Description)
- [Feature Engineering](#feature-Engineering)
- [Primary Analysis](#primary-Analysis)
- [Key Dashboard Metrics](#key-Dashbord-Metrics)
- [Dashboard Features](#dashboard-Features)
- [Tools And Techniques](#tools-and-Techniques)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

---

## 📸 Visual Preview
![Screenshot 2025-04-29 175651](https://github.com/user-attachments/assets/9ad63ffe-d6d6-4899-9159-f7ba509e5ee8)


---
🏗️ Project Structure
The workbook consists of three sheets:

1. 📂 Data: Contains raw sales data with metrics like Sales, Profit, Target Sales, Customer Satisfaction, etc.
2. 📊 Pivot: Includes aggregated data, KPIs, and pivot tables for analysis.
3. 📌 DashBoard: (Currently empty) Intended for visualizing key metrics and trends.


---

## 🔗 Data Source
This dataset was synthetically generated for internal analytics demonstration and contains entries mimicking real-world regional sales data across South America.
Scope: Regional sales performance across countries (Argentina, Brazil, Colombia, Ecuador, Peru).
Timeframe: January 2023 - December 2023.

## 🧾 Dataset Description
The primary Data sheet contains:
Date, Month, Quarter

Region, Country

Sales, Profit, Target Sales

No of Customers

Completion Rates for Sales, Profit, and Customers

Customer Satisfaction (qualitative feedback)

Score (satisfaction rating from 1–10)

---

## 🛠️ Feature Engineering (Excel Formula-Based)

Derived Columns:

Month extracted from Date using =TEXT(Date, "mmm").

Quarter calculated as ="Q"&ROUNDUP(MONTH(Date)/3,0).

Aggregated Metrics:

Sum of Sales/Target Sales by Month/Region/Country.

Average completion rates (Sales Completion Rate = 85.56%, Profit Completion Rate = 85.49%).

KPI Calculations:

Sales vs Target Sales Rate = 94.25% (cell T6 in Pivot sheet).

---

## 🔍 Primary Analysis
Sales Performance:

Total Sales: 157,361 vs Target Sales: 166,999 (94.25% achievement).

Top Month: Jan (Sales: 12,900) | Lowest: Sep (Sales: 3,600).

Regional Breakdown:

East dominated sales (50,045) but had lower profit margins (Profit/Sales = 90%).

North had the lowest sales (22,921) but high profit completion (99% in Nov).

Customer Satisfaction:

Speed scored highest (96/336), while Availability scored lowest (41/336).

---

## 📈 Key Dashboard Metrics (From Pivot Sheet)

✅Avg. Sales Completion Rate	85.56%

✅Avg. Profit Completion Rate	85.49%

✅Sales vs Target Rate	94.25%

✅Total Customers	9,360

✅Top Country (Sales)	Brazil (63,874)

---
## 🧩 Dashboard Features

📆 Monthly & Quarterly performance trends

🌎 Regional comparisons of Profit & Sales

🤝 Customer Satisfaction breakdown by score and type

🔎 KPI Highlights with auto-updating formulas

📊 Embedded PivotTables for dynamic slicing

---

## 🧰 Tools And Techniques
Microsoft Excel (Power Query, PivotTable, Conditional Formatting)

Manual Feature Engineering

KPI Design and Measurement

Visual Dashboards (with slicers and filters)

---

## 💡 INSIGHTS
Underperformance in Sep/Dec: Sales dropped significantly (Sep: 3,600; Dec: 3,800).

Profit-Sales Mismatch: East region has high sales but lower profit margins.

Customer Pain Points: "Availability" and "Hygiene" need improvement (low satisfaction scores).

The West and East regions consistently outperformed in terms of profit and sales.

Months like January and March exceeded sales targets, while April underperformed.

---
## 🚀 RECOMMENDATIONS
🔁 Improve customer outreach to close the gap in customer target metrics.

📈 Reallocate resources towards high-performing regions for maximized ROI.

🧹 Investigate satisfaction factors like "Hygiene" and "Quality" which correlated with low scores.

📅 Focus on underperforming months (e.g., April) with targeted marketing or promotions.

---
