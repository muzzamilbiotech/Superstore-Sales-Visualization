# 📊 Superstore Sales Visualization — Week 2 Project

> **Internship**: Data Analytics Intern @ Afynix Digital  
> **Author**: Muzzamil Hussain  
> **Duration**: Week 2 of 6 | Focus: Data Visualization & Storytelling  
> **GitHub**: [github.com/muzzamilbiotech](https://github.com/muzzamilbiotech)

---

## 🗂 Project Overview

This project delivers a complete **data visualization and storytelling analysis** on the Superstore Sales dataset (1,000 orders, 2021–2024). Every chart is built around one core principle from the assignment brief: *every visualization must answer — "So what? Why does this matter?"*

---

## 📁 Repository Structure

```
├── superstore_raw.csv               # Source dataset (1000 orders, 2021–2024)
├── superstore_visualization.R       # Full R script
├── w2_fig1_cat_sales_profit.png     # Sales vs Profit by Category
├── w2_fig2_time_series.png          # Monthly Sales Trend (2021–2024)
├── w2_fig3_regional.png             # Regional Performance Analysis
├── w2_fig4_subcategory_profit.png   # Sub-category Profit Deep Dive
├── w2_fig5_segment_discount.png     # Segment & Discount Impact
├── w2_linkedin_card.png             # LinkedIn post visual
└── README.md
```

---

## 📊 Charts Built & Business Insight ("So What?")

### Fig 1 — Sales vs Profit by Category (Grouped Bar)
**So what?** Technology generates the highest sales ($298K), but Office Supplies has the best profit margin (22%). Furniture has high revenue but thin margins — a strategic warning sign.

### Fig 2 — Monthly Sales Trend, 2021–2024 (Time Series Line Chart)
**So what?** Consistent year-on-year growth is confirmed. 2024 outperforms all prior years. Q4 spikes indicate seasonal purchasing behaviour that inventory planning should account for.

### Fig 3 — Regional Performance (Side-by-Side Bar Charts)
**So what?** West region leads in both sales volume and profit margin. South consistently underperforms — warranting a strategic review of pricing, product mix, or sales team allocation.

### Fig 4 — Sub-category Profit Deep Dive (Diverging Bar)
**So what?** Several sub-categories (Tables, Bookcases) are loss-makers despite positive sales. Selling more of a loss-making product makes the problem worse, not better.

### Fig 5 — Segment & Discount Impact (Donut + Bar)
**So what?** Discounts above 20% reliably flip orders from profit to loss. The Consumer segment accounts for 52% of revenue but absorbs the most discounting — a policy review is needed.

---

## 🛠 Tools & Libraries

**R**: `ggplot2`, `dplyr`, `lubridate`, `scales`, `gridExtra`  
**Python (mirror)**: `pandas`, `matplotlib`, `numpy`

---

## 📌 How to Run

```r
source("superstore_visualization.R")
```

---

*Part of a 6-week Data Analytics Internship at Afynix Digital*
