# Sales-

# Sales Dashboard – README

## Project Overview

The **Sales Dashboard** is an interactive Power BI dashboard developed to analyze sales performance, profit trends, order activity, and product-category relationships. The dashboard provides a centralized business intelligence solution for monitoring organizational sales KPIs and understanding operational performance across different categories and regions. 

---

# Dashboard Objectives

This dashboard is designed to help users:

* Monitor total sales and profit
* Analyze order performance
* Compare category-wise sales
* Track monthly sales trends
* Understand quantity and product performance
* Filter sales data dynamically

---

# Key Performance Indicators (KPIs)

The dashboard highlights important business metrics:

| KPI            | Value |
| -------------- | ----- |
| Total Profit   | 1M    |
| Order Count    | 100   |
| Distinct Count | 4     |
| Total Sales    | 569M  |

These KPIs provide a quick summary of overall business performance. 

---

# Dashboard Visualizations

## 1. Sales by Profit

Line chart displaying profit performance over sales ranges.

### Purpose

* Monitor profit fluctuations
* Identify high-profit sales ranges
* Analyze profitability patterns

---

## 2. Sales by Category

Donut chart comparing sales contribution by category.

### Example Insights

* One category contributes approximately 64.93%
* Another contributes 35.07%

### Purpose

* Compare category performance
* Identify dominant product categories

---

## 3. Sales by Quantity

Line/Area chart analyzing quantity-based sales trends.

### Purpose

* Understand sales volume patterns
* Track quantity movement across products

---

## 4. Sales by Product and Category

Scatter/Bubble chart visualizing:

* Product sales
* Category relationships
* Sales distribution

### Purpose

* Compare product performance
* Identify high-performing products

---

## 5. Category by Month

Horizontal bar chart displaying monthly category performance.

### Months Included

* January
* February
* March
* April

### Purpose

* Analyze monthly sales trends
* Compare seasonal performance

---

# Filters & Slicers

The dashboard includes interactive filters for:

* Category
* Cost
* Region
* Product

These slicers allow users to dynamically explore and analyze sales data.

---

# Dashboard Design

## Theme

The dashboard uses a professional purple-themed corporate design featuring:

* Purple gradient background
* White typography
* Rounded visual containers
* Modern KPI cards

## UI Features

* Interactive slicers
* Responsive chart arrangement
* Clean business analytics layout
* Minimal and professional appearance

---

# Tools & Technologies Used

* Power BI Desktop
* DAX Measures
* Power Query
* Data Modeling
* Interactive Visualizations

---

# Suggested DAX Measures

## Total Sales

```DAX id="bz7lrm"
Total Sales = SUM(Sales[Sales_Amount])
```

## Total Profit

```DAX id="7rjqjw"
Total Profit = SUM(Sales[Profit])
```

## Order Count

```DAX id="vjlwm5"
Order Count = DISTINCTCOUNT(Sales[Order_ID])
```

## Distinct Product Count

```DAX id="0ppfwp"
Distinct Product Count =
DISTINCTCOUNT(Sales[Product])
```

---

# Business Insights

* A major portion of sales comes from one dominant category.
* Profit varies significantly across sales ranges.
* Sales quantity trends indicate peak performance periods.
* Monthly analysis helps identify seasonal demand patterns.
* Product-category comparison supports inventory planning.

---

# Future Improvements

Possible enhancements include:

* Regional sales map visualization
* Profit margin analysis
* Customer segmentation
* Sales forecasting using AI
* Drill-through product detail pages
* Mobile-responsive layout
* Real-time sales tracking

---

# Dataset Fields Used

The dashboard analyzes:

* Sales Amount
* Profit
* Quantity
* Product
* Category
* Cost
* Region
* Order ID
* Month

---

# Conclusion

The **Sales Dashboard** provides a complete sales analytics solution using Power BI. It combines KPI monitoring, trend analysis, category comparison, and interactive filtering to help businesses make informed sales and operational decisions through data-driven insights. 
