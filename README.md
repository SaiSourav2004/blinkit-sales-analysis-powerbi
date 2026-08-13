````markdown
# BlinkIT Sales Analysis | Power BI Dashboard

> An interactive Business Intelligence dashboard built with Microsoft Power BI to analyze BlinkIT sales, product performance, and outlet performance.

---

## Overview

This project focuses on transforming BlinkIT grocery sales data into an interactive and business-focused Power BI dashboard.

The analysis combines data modeling, table relationships, DAX measures, KPIs, interactive filters, and visual analytics to provide a clear view of sales performance across products, outlets, locations, and outlet characteristics.

The main goal of this project is to understand how Power BI can transform raw business data into meaningful insights and support data-driven decision-making.

---

## Business Objective

The primary objective of this project is to analyze BlinkIT's sales data and understand:

- Which product categories contribute the most to sales
- Which outlet types perform better
- How sales are distributed across outlet locations
- How Low Fat and Regular products contribute to sales
- How outlet size affects sales
- How sales vary across outlet establishment years
- How actual sales compare with the target

---

## Project Workflow

```text
Raw Data
    ↓
Data Preparation
    ↓
Data Modeling
    ↓
Table Relationships
    ↓
DAX Measures & KPIs
    ↓
Interactive Visualizations
    ↓
Dashboard Development
    ↓
Business Insights
````

---

## Dataset

The project uses multiple related tables to organize the BlinkIT grocery sales data.

### Tables Used

* BlinkIT Grocery Data
* Items
* Items Content
* Outlet Info
* Outlet Location
* Cities

The main sales table contains information such as:

* Item Fat Content
* Item Identifier
* Item Type
* Item Visibility
* Item Weight
* Outlet Establishment Year
* Outlet Identifier
* Outlet Location Type
* Outlet Size
* Outlet Type
* Sales
* Rating

The supporting tables provide additional information related to items, outlets, locations, and cities.

---

## Data Model

The project uses a relational data model created in Power BI.

Multiple tables are connected through relationships so that information from different tables can work together correctly across the report.

The data model was created before developing the report pages to ensure that filters, calculations, KPIs, and visualizations work consistently throughout the dashboard.

---

## Power BI Workflow

The project was developed using the following workflow:

1. Loaded the available datasets into Power BI
2. Prepared and organized the data
3. Created relationships between the tables
4. Built DAX measures and KPIs
5. Created interactive slicers
6. Designed business-focused visualizations
7. Developed three report pages
8. Analyzed product and outlet performance
9. Derived key business insights
10. Presented the final dashboard

---

# Dashboard Pages

The Power BI report contains three interactive analysis pages.

---

## 01 | Executive Dashboard

The main dashboard provides an overall view of BlinkIT's sales performance.

### Key Performance Indicators

| KPI                      |   Value |
| ------------------------ | ------: |
| Total Sales              |   1.20M |
| Average Sales per Outlet | 120.17K |
| Average Rating           |    3.92 |
| Target Sales             |   1.32M |
| Sales per Kg             |   13.24 |

### Visualizations

* Sales vs Target
* Total Sales by Outlet Establishment Year
* Total Sales by Item Fat Content
* Total Sales by Item Type
* Target Sales by Outlet Location Type
* Sales by Outlet Type

### Interactive Filters

The dashboard includes slicers for:

* Outlet Location Type
* Outlet Type
* Item Type
* Item Fat Content

These filters allow users to dynamically explore the dashboard from different business perspectives.

---

## 02 | Product Performance Analysis

This page focuses on product-level sales performance.

### Key Performance Indicators

| KPI                    |        Value |
| ---------------------- | -----------: |
| Total Sales            | 12,01,681.49 |
| Product Categories     |           16 |
| Low Fat Sales %        |       64.60% |
| Average Product Rating |         3.92 |

### Visualizations

* Total Sales by Item Type
* Total Sales and Average Sales per Outlet by Outlet Type
* Sales Performance Score
* Total Sales by Item Fat Content
* Total Sales by Item Type and Item Fat Content

### Key Findings

* Fruits and Vegetables and Snack Foods are among the highest-selling categories.
* Low Fat products contribute a larger share of total sales than Regular products.
* Product-level comparisons help identify categories with stronger sales contribution.

---

## 03 | Outlet Performance Analysis

This page focuses on outlet-level performance based on outlet type, location, size, and establishment year.

### Key Performance Indicators

| KPI                    |   Value |
| ---------------------- | ------: |
| Total Outlet Sales     | 120.17K |
| Total Outlets          |      16 |
| Average Sales per Item |  140.99 |
| Sales Achieved         |   90.91 |

### Visualizations

* Total Sales by Item Type
* Total Sales by Outlet Type
* Total Sales by Outlet Location Type
* Total Sales by Outlet Establishment Year
* Total Sales by Outlet Size

### Key Findings

* Supermarket Type1 has the highest sales contribution among the outlet types shown.
* Small and Medium outlets have very similar sales contributions.
* High-size outlets contribute a comparatively lower share of sales.
* Sales performance varies across different outlet establishment years.

---

# Key Business Insights

### Product Performance

Fruits and Vegetables and Snack Foods are among the strongest-performing product categories.

### Fat Content

Low Fat products contribute a larger share of total sales compared with Regular products.

### Outlet Performance

Supermarket Type1 contributes the highest sales among the outlet types shown in the dashboard.

### Outlet Size

Small and Medium outlets contribute similar shares of total sales, while High-size outlets contribute a lower share.

### Outlet Location

Sales vary across Tier 1, Tier 2, and Tier 3 outlet locations, allowing location-wise performance comparison.

### Sales Target

The Sales vs Target visual provides a quick comparison between current sales performance and the target.

---

# Dashboard Preview

### Executive Dashboard

![Executive Dashboard](screenshots/dashboard.png)

### Product Performance Analysis

![Product Performance Analysis](screenshots/product-analysis.png)

### Outlet Performance Analysis

![Outlet Performance Analysis](screenshots/outlet-performance.png)

---

# Project Demo

A short walkthrough video of this project is available on my LinkedIn profile.

The video covers:

* Data Model
* Table View
* Executive Dashboard
* Interactive Filters
* KPI Cards
* Product Performance Analysis
* Outlet Performance Analysis
* Key Business Insights
* Final Conclusion

**LinkedIn Demo:**
[View Project Walkthrough](YOUR_LINKEDIN_POST_LINK_HERE)

---

# Tools & Technologies

| Category            | Tools                                  |
| ------------------- | -------------------------------------- |
| BI Platform         | Microsoft Power BI                     |
| Data Transformation | Power Query                            |
| Calculations        | DAX                                    |
| Data Modeling       | Power BI Relationships                 |
| Visualization       | Power BI                               |
| Analysis            | Business Intelligence & Data Analytics |

---

# Repository Structure

```text
blinkit-sales-analysis-powerbi/
│
├── datasets/
│   ├── BlinkIT Grocery Data
│   ├── Items
│   ├── Items Content
│   ├── Outlet Info
│   ├── Outlet Location
│   └── Cities
│
├── screenshots/
│   ├── dashboard.png
│   ├── product-analysis.png
│   └── outlet-performance.png
│
├── BlinkIT_Sales_Analysis_Dashboard.pbix
│
└── README.md
```

---

# Conclusion

This project demonstrates how Power BI can transform raw business data into an interactive dashboard for sales, product, and outlet analysis.

The dashboard brings multiple business perspectives together and makes it easier to compare performance, identify patterns, and support data-driven business decisions.

---

# Author

**Sai Sourav Panigrahi**

Data Science | Data Analytics | Machine Learning | AI

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Building Power BI data models
* Creating table relationships
* Working with DAX measures
* Designing KPI cards
* Creating interactive slicers
* Building business-focused dashboards
* Analyzing sales and outlet performance
* Presenting data-driven business insights

```
```
