<div align="center">

# 📊 BlinkIT Sales Analysis | Power BI Dashboard

**Interactive Business Intelligence Dashboard for Sales, Product & Outlet Performance Analysis**

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)](https://powerbi.microsoft.com/)
[![Power Query](https://img.shields.io/badge/Power%20Query-1177BB?style=for-the-badge\&logo=microsoft\&logoColor=white)](https://learn.microsoft.com/power-query/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-0078D4?style=for-the-badge\&logo=microsoft\&logoColor=white)](https://learn.microsoft.com/dax/)

*Transforming retail sales data into interactive, business-focused insights.*

</div>

---

## 📖 Project Overview

The **BlinkIT Sales Analysis Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI** to analyze retail sales performance across products, outlets, locations, and outlet characteristics.

The project follows an end-to-end analytics workflow covering **data preparation, data modeling, table relationships, DAX measures, KPI development, interactive filtering, and dashboard visualization**.

The final dashboard provides a consolidated view of sales performance and enables users to explore product and outlet-level trends through interactive report pages.

---

## 🎯 Business Objective

The primary objective of this project is to analyze BlinkIT sales data and generate meaningful insights into overall sales performance, product contribution, and outlet performance.

### Key Questions

* How do actual sales compare with the defined sales target?
* Which product categories contribute the most to total sales?
* How are sales distributed between Low Fat and Regular products?
* How does outlet type relate to sales performance?
* How does outlet size affect sales distribution?
* How do sales vary across outlet location types?
* How does sales performance vary across outlet establishment years?

---

## 📂 Dataset

The project uses multiple related tables containing product, outlet, location, and sales information.

### Data Tables Used

| Table                      | Purpose                    |
| -------------------------- | -------------------------- |
| `BlinkIT Grocery Data (2)` | Main sales fact table      |
| `Items`                    | Item-related information   |
| `Items Content`            | Product content attributes |
| `Outlet Info`              | Outlet-related information |
| `Outlet Location`          | Outlet location details    |
| `Cities`                   | City-level information     |

### Data Points Included

**Product Attributes**

* Item Type
* Item Fat Content
* Item Weight
* Item Visibility
* Item Identifier

**Outlet Attributes**

* Outlet Establishment Year
* Outlet Size
* Outlet Location Type
* Outlet Type
* Outlet Identifier

**Performance Metrics**

* Sales
* Rating

---

## 🧩 Data Model

The project uses a relational data model created in **Power BI Model View**.

The central sales table is connected with supporting dimension tables through identifier keys, allowing the report to perform cross-table analysis and dynamic filtering.

### Model Components

* `BlinkIT Grocery Data (2)` — Central sales fact table
* `Items` — Product-related attributes
* `Items Content` — Additional product information
* `Outlet Info` — Outlet attributes
* `Outlet Location` — Location-related attributes
* `Cities` — City-level information

### Relationship Keys

The model uses keys including:

* `OutletKey`
* `OutletLocationKey`
* `ItemKey`
* `ItemContentKey`
* `CitiesKey`

This model provides the foundation for DAX calculations, KPIs, slicers, and report visualizations.

---

## 🔄 Project Workflow

```text
Data Preparation
        ↓
Data Modeling
        ↓
Table Relationships
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Interactive Filters
        ↓
Data Visualization
        ↓
Dashboard Development
        ↓
Business Insights
```

---

# 📊 Dashboard Pages

The Power BI report consists of three specialized analysis pages:

1. Executive Dashboard
2. Product Performance Analysis
3. Outlet Performance Analysis

---

## 01 | Executive Dashboard

The **Executive Dashboard** provides a high-level view of overall sales performance and allows users to explore the data through interactive filters.

### Key Performance Indicators

| KPI                          |       Value |
| ---------------------------- | ----------: |
| **Total Sales**              |   **1.20M** |
| **Average Sales per Outlet** | **120.17K** |
| **Average Rating**           |    **3.92** |
| **Target Sales**             |   **1.32M** |
| **Sales per Kg**             |   **13.24** |

### Visualizations

* **Sales vs Target** — Tracks actual sales against the defined target.
* **Total Sales by Outlet Establishment Year** — Shows sales variation across establishment years.
* **Total Sales by Item Fat Content** — Compares sales contribution from Low Fat and Regular products.
* **Total Sales by Item Type** — Compares sales across product categories.
* **Target Sales by Outlet Location Type** — Compares target-related values across location tiers.
* **Sales by Outlet Type** — Compares sales across different outlet formats.

### Interactive Filters

* Outlet Location Type
* Outlet Type
* Item Type
* Item Fat Content

### Key Insights

* Total sales are approximately **1.20M**, compared with a target of approximately **1.32M**.
* Low Fat products contribute a larger share of sales than Regular products.
* Sales performance varies across outlet types, locations, and establishment years.
* The dashboard provides a consolidated view of overall sales performance.

---

## 02 | Product Performance Analysis

The **Product Performance Analysis** page focuses on sales contribution across different product categories and item characteristics.

### Key Performance Indicators

| KPI                        |            Value |
| -------------------------- | ---------------: |
| **Total Sales**            | **1,201,681.49** |
| **Product Categories**     |           **16** |
| **Low Fat Sales %**        |       **64.60%** |
| **Average Product Rating** |         **3.92** |

### Visualizations

* **Total Sales by Item Type** — Compares sales across all product categories.
* **Total Sales and Average Sales per Outlet by Outlet Type** — Compares sales performance across outlet formats.
* **Sales Performance Score** — Provides a visual summary of the performance metric.
* **Total Sales by Item Fat Content** — Compares Low Fat and Regular product sales.
* **Total Sales by Item Type and Item Fat Content** — Provides a category-level comparison of fat-content sales.

### Key Insights

* **Fruits and Vegetables** and **Snack Foods** are among the highest-performing product categories.
* Low Fat products contribute approximately **64.60%** of total sales.
* Product-level comparisons help identify categories with stronger sales contribution.
* The combination of Item Type and Fat Content provides a deeper view of product-level sales distribution.

---

## 03 | Outlet Performance Analysis

The **Outlet Performance Analysis** page focuses on sales performance across outlet type, location, size, and establishment year.

### Key Performance Indicators

| KPI                        |       Value |
| -------------------------- | ----------: |
| **Total Outlet Sales**     | **120.17K** |
| **Total Outlets**          |      **16** |
| **Average Sales per Item** |  **140.99** |
| **Sales Achieved**         |   **90.91** |

### Visualizations

* **Total Sales by Item Type** — Shows product-category sales contribution.
* **Total Sales by Outlet Type** — Compares sales across outlet formats.
* **Total Sales by Outlet Location Type** — Compares sales across Tier 1, Tier 2, and Tier 3 locations.
* **Total Sales by Outlet Establishment Year** — Shows sales variation across establishment years.
* **Total Sales by Outlet Size** — Compares sales contribution across Small, Medium, and High outlet sizes.

### Key Insights

* **Supermarket Type 1** is the highest-contributing outlet type in terms of sales.
* Sales contributions vary across Small, Medium, and High outlet sizes.
* Small and Medium outlets account for substantial portions of the sales distribution.
* Sales performance varies across outlet location types and establishment years.

---

# 💡 Key Business Insights

### Product Performance

**Fruits and Vegetables** and **Snack Foods** are among the strongest-performing product categories in the analysis.

### Product Fat Content

**Low Fat products account for approximately 64.60% of total sales**, representing a larger sales contribution than Regular products.

### Outlet Type

**Supermarket Type 1** contributes the highest sales among the outlet types represented in the dashboard.

### Outlet Size

Sales are distributed across Small, Medium, and High outlet sizes, with Small and Medium outlets contributing substantial portions of total sales.

### Outlet Location

The dashboard enables comparison of sales performance across **Tier 1, Tier 2, and Tier 3** outlet locations.

### Sales Target

The Executive Dashboard provides a direct comparison between actual sales and the defined target, making overall performance easier to monitor.

---

# 🖼️ Dashboard Preview

### Executive Dashboard

![Executive Dashboard](<img width="1364" height="777" alt="image" src="https://github.com/user-attachments/assets/5d0dd28e-9d1a-4786-9b29-e0eeb6b69b03" />
)

### Product Performance Analysis

![Product Performance Analysis](<img width="1433" height="772" alt="image" src="https://github.com/user-attachments/assets/9f8a183e-98df-41c2-bcf8-9b66659eb65c" />
)

### Outlet Performance Analysis

![Outlet Performance Analysis](<img width="1435" height="801" alt="image" src="https://github.com/user-attachments/assets/f3644272-564d-4dff-8c09-4a79fd19d0cf" />
)

---

# 🎥 Project Demo

A complete video walkthrough of the Power BI project is available on LinkedIn.

The walkthrough covers:

* Power BI Data Model
* Table View
* Executive Dashboard
* KPI Cards
* Interactive Filters
* Product Performance Analysis
* Outlet Performance Analysis
* Key Business Insights
* Final Conclusion

**[View Project Walkthrough on LinkedIn](https://www.linkedin.com/posts/saisourav-panigrahi_powerbi-dataanalytics-datascience-ugcPost-7493642185578520576-FutZ/)**

---

# 🛠️ Tools & Technologies

| Category                | Technology                             |
| ----------------------- | -------------------------------------- |
| **BI Platform**         | Microsoft Power BI                     |
| **Data Transformation** | Power Query                            |
| **Calculations**        | DAX                                    |
| **Data Modeling**       | Power BI                               |
| **Visualization**       | Power BI                               |
| **Analysis**            | Business Intelligence & Data Analytics |

---

# 📁 Repository Structure

```text
blinkit-sales-analysis-powerbi/
│
├── datasets/
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

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Power BI data modeling
* Table relationships
* Power Query
* DAX measures
* KPI development
* Interactive slicers
* Dashboard design
* Data visualization
* Product performance analysis
* Outlet performance analysis
* Business-oriented data analysis
* Insight generation

---

# 📌 Conclusion

This project demonstrates an end-to-end Power BI workflow for transforming retail sales data into an interactive Business Intelligence dashboard.

By combining **data modeling, relationships, DAX measures, KPI development, interactive filters, and data visualization**, the dashboard provides a structured view of sales, product performance, and outlet performance.

The project highlights how business data can be transformed into clear and interactive insights that support data-driven analysis and decision-making.

---

# 👤 Author

**Sai Sourav Panigrahi**

*Data Science | Data Analytics | Machine Learning | AI*
