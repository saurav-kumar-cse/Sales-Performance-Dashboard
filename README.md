# Sales-Performance-Dashboard
# 📊 Sales Performance Dashboard — Excel

## Overview

An end-to-end interactive sales analytics dashboard built in Microsoft Excel to track and evaluate the performance of **141 Sales Executives** across **8 regions** in a telecom company. The dashboard enables management to instantly identify top and bottom performers based on total sales and target achievement.

---

## 🗂️ Project Structure

```
Sales_Performance_dashboard.xlsm
│
├── RAW DATA Sheet        → Employee records with daily sales & KPIs
└── DASHBOARD Sheet       → Leaderboards, Charts, Slicers, Macros
```

---

## 📁 Dataset Details

| Field | Description |
|---|---|
| Emp Code | Unique employee ID (e.g. Mum-TCL001) |
| Sales Executive | Employee name |
| Region | Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi, Surat |
| Day 1 – Day 5 | Daily sales figures |
| Total Sales | Sum of Day 1 to Day 5 |
| Target | Fixed at 500 for all employees |
| Target Hit % | Total Sales / Target |
| Away From Target % | 1 − Target Hit % |

---

## 🔧 Tools & Features Used

| Tool/Feature | Purpose |
|---|---|
| **Formulas** | SUM, percentage calculations for KPIs |
| **Pivot Tables** | Aggregated sales data by region & executive |
| **Charts** | Bar charts for top/bottom performer leaderboards |
| **Slicers** | Filter dashboard by region, performance category |
| **Macros (VBA)** | Assigned to slicers for automated filtering & refresh |
| **Conditional Formatting** | Visual highlights for high/low performers |

---

## 📈 Dashboard KPIs

- **Total Sales** per executive
- **Target Hit %** — how close to the 500 target
- **Away From Target %** — gap from target
- **Top 5 Performers** by Total Sales
- **Bottom 5 Performers** by Total Sales
- **Top 5 by Target Hit %**
- **Bottom 5 by Away From Target %**

---

## 🏆 Sample Insights

| Rank | Top Performers | Sales |
|---|---|---|
| 1 | Anikuttan | 382 |
| 2 | Ritu Bhatnagar | 371 |
| 3 | Rashid | 340 |

| Rank | Bottom Performers | Sales |
|---|---|---|
| 1 | Praveen Kumar | 166 |
| 2 | Mubeen Khan | 209 |
| 3 | Sushma Khandelwal | 213 |

---

## 🚀 How to Use

1. Open `Chapter_10_End_to_End_Project_using_Excel.xlsm` in Microsoft Excel
2. Enable Macros when prompted
3. Go to the **DASHBOARD** sheet
4. Use **Slicers** to filter by Region or Performance Category
5. Macros auto-refresh the leaderboard rankings on filter

---

## 💡 Skills Demonstrated

`Excel` · `Pivot Tables` · `Charts` · `Slicers` · `Macros (VBA)` · `KPI Design` · `Dashboard Design` · `Data Analysis`

---

## 👤 Author

**Saurav**
CSE Graduate | Aspiring Data Analyst
📍 Gurgaon, India
