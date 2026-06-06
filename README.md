# Ecommerce Sales Analytics Dashboard

## Project Overview

This project presents an interactive Ecommerce Sales Analytics Dashboard developed using Power BI. The dashboard provides a comprehensive view of sales performance, customer behavior, product performance, and geographical sales distribution. It enables businesses to monitor key metrics, identify trends, and make data-driven decisions.

---

## Project Objective

The objective of this project is to analyze ecommerce sales data and transform raw transactional information into actionable business insights.

The dashboard helps stakeholders:

* Monitor overall business performance.
* Track revenue and sales growth.
* Analyze customer purchasing behavior.
* Identify top-performing products.
* Evaluate customer retention and engagement.
* Understand geographical sales distribution.
* Support strategic business decision-making.

---

## Tools & Technologies Used

* Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Microsoft Excel / CSV Dataset

---

## Key Performance Indicators (KPIs)

| KPI                   | Value   |
| --------------------- | ------- |
| Total Revenue         | 105.40M |
| Total Quantity Sold   | 6M      |
| Average Unit Price    | $17.56  |
| Total Customers       | 9,191   |
| Active Customers      | 9,191   |
| Returning Customers % | 1.00%   |

---

## Dashboard Features

### Sales Performance Analysis

* Revenue Tracking
* Quantity Sold Analysis
* Average Unit Price Monitoring
* Monthly Sales Trend Analysis
* Year-over-Year Performance Comparison

### Customer Insights

* Total Customer Analysis
* Active Customer Tracking
* Returning Customer Percentage
* Customer Order Bucket Segmentation

### Product Insights

* Product-wise Revenue Analysis
* Product-wise Quantity Analysis
* Top Selling Products Identification
* Product Performance Comparison

### Geographic Analysis

* Location-wise Revenue Distribution
* Sales Heatmap Visualization
* Regional Performance Comparison

---

## DAX Measures Used

### Total Revenue

```DAX
Total Revenue =
SUM(Sales[total_price])
```

### Total Quantity Sold

```DAX
Total Quantity Sold =
SUM(Sales[quantity])
```

### Average Unit Price

```DAX
Average Unit Price =
AVERAGE(Sales[unit_price])
```

### Total Customers

```DAX
Total Customers =
DISTINCTCOUNT(Sales[customer_id])
```

### Active Customers

```DAX
Active Customers =
DISTINCTCOUNT(Sales[customer_id])
```

### Returning Customer Percentage

```DAX
Returning Customer % =
DIVIDE([Returning Customers], [Total Customers])
```

### Previous Year Revenue

```DAX
Previous Year Revenue =
CALCULATE(
    [Total Revenue],
    SAMEPERIODLASTYEAR(Date[Date])
)
```

### Revenue Growth Percentage

```DAX
Revenue Growth % =
DIVIDE(
    [Total Revenue] - [Previous Year Revenue],
    [Previous Year Revenue]
)
```

---

## Business Insights

1. The business generated over **105.40 Million** in revenue, indicating strong market performance.

2. More than **6 Million units** were sold across all product categories.

3. The average selling price remained around **$17.56**, reflecting consistent pricing strategies.

4. Dhaka emerged as the highest revenue-generating location, contributing significantly to overall sales.

5. Product category **PK** achieved the highest quantity sold, with approximately **228K units**.

6. A limited number of products contributed to a large percentage of total revenue, following the Pareto Principle.

7. The business maintained a customer base of over **9,000 customers**, demonstrating strong customer acquisition.

8. Returning customers contributed meaningfully to overall sales, highlighting customer loyalty.

9. Monthly sales trends reveal recurring fluctuations, suggesting seasonal purchasing patterns.

10. Geographic analysis indicates that a few regions drive the majority of business revenue.

---

## Skills Demonstrated

* Power BI Dashboard Development
* Data Cleaning & Transformation
* Data Modeling
* DAX Measure Development
* Business Intelligence Reporting
* KPI Design
* Sales Analytics
* Customer Analytics
* Product Analytics
* Data Visualization
* Geographic Analysis
* Business Insight Generation

---

## Dashboard Screenshots

### Sales Overview Dashboard

Insert Screenshot Here

### Customer & Product Insights Dashboard

Insert Screenshot Here

---

## Project Outcomes

This dashboard enables stakeholders to:

* Monitor key business metrics in real time.
* Identify top-performing products and regions.
* Improve customer retention strategies.
* Optimize pricing and inventory decisions.
* Make informed business decisions using data-driven insights.

---

## Author

**Badal Singh**

Aspiring Data Analyst | Power BI Developer | SQL | Python | Excel

GitHub: https://github.com/Badalsingh05

LinkedIn: https://www.linkedin.com/in/badal-singh-299947206
