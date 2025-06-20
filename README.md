# Global-Superstore-Sale-Analysis---Data-Analysis-and-Visualization-Project

## Overview
This project analyzes global sales performance using the "Global Superstore" dataset. It highlights key trends across countries, product categories, shipping modes, and time, and presents interactive Tableau dashboards for business insights.

---

## Dataset

- **Source**: [Kaggle – Global Superstore Dataset](https://www.kaggle.com/datasets/kapiljoshi/global-superstore)
- **File Name**: `Global Superstore.xls`
- **Time Frame**: 2011–2014
- **Data Size**: ~18,000 rows
- **Fields Include**:
  - Order Date, Ship Date, Region, Country, Category, Sub-Category
  - Sales, Quantity, Discount, Profit
  - Customer Name, Segment, Shipping Mode

---

## Key Questions Addressed

- Which **regions and countries** generate the most profit and sales?
- Which **products and sub-categories** are underperforming?
- How do **discounts** impact profitability?
- What are the **monthly and yearly trends** in sales and profit?
- How does **shipping mode** affect delivery times and revenue?

---

## Tableau Dashboard

**Download TWBX file**:  
[Global Superstore Dashboard (TWBX)](https://public.tableau.com/views/GlobalSuperstore_twbx_16535352977810/Sheet24)

### Dashboard Features

1. **Sales & Profit by Region and Country**
   - Dynamic maps showing top-performing countries
   - Regional drill-down for comparative analysis

2. **Category & Sub-Category Analysis**
   - Heatmaps showing profit margins and sales volume
   - Bubble charts for identifying loss-generating products

3. **Customer Segments**
   - Profitability by segment (Consumer, Corporate, Home Office)
   - Top 10 customers by profit

4. **Shipping Mode & Delivery Delays**
   - Avg. delivery time across ship modes
   - Impact of shipping method on customer satisfaction

5. **Time Series Trends**
   - Monthly and yearly trends for sales and profits
   - Seasonality patterns across categories

---

## Key Insights

- **United States, India, and Australia** generated the highest overall sales.
- **Tables**, **Bookcases**, and **Machines** are among the **least profitable sub-categories**, often due to high discounts or shipping costs.
- **High discounts** do not always correlate with high sales — some products sell well at low discounts and still generate better margins.
- **Standard Class** shipping is the most used mode but often results in higher delivery delays compared to **Second Class** or **First Class**.
- **Q4 consistently shows the highest sales volume**, likely due to holiday season purchasing behavior.

---

## Tools & Technologies

| Tool            | Purpose                                  |
|-----------------|-------------------------------------------|
| Tableau Desktop | Interactive dashboards & visual analytics |
| Excel           | Source file format                        |
| Python          | Data preprocessing (optional)             |
| Pandas          | Tabular data manipulation                 |
| Jupyter         | Notebook for EDA                          |

---
