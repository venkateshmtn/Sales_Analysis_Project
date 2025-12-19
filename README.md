# Retail Sales Analytics & Customer Insights

## Project Overview

This project is an **end-to-end Data Analyst portfolio project** that demonstrates how to use **Python, MS SQL Server and Power BI** together to solve real-world business problems in the retail domain.

The goal is to analyze retail sales data to uncover **sales trends, customer behavior, product performance, and regional insights**, and present them through **interactive dashboards** for business stakeholders.

---

## Business Objectives

* Monitor overall sales performance
* Analyze **MTD, QTD, YTD, and YOY growth**
* Identify **top customers and products**
* Understand regional and segment-wise performance
* Improve decision-making using data-driven insights

---

## Tools & Technologies Used

| Tool                                   | Purpose                                          |
| -------------------------------------- | ------------------------------------------------ |
| **Python (Pandas, NumPy)**             | Data cleaning, feature engineering, EDA          |
| **MS SQL Server**                      | Star schema design, data modeling, SQL analytics |
| **Power BI**                           | Data visualization, DAX, dashboards, RLS         |
| **Kaggle Dataset**                     | Source data                                      |
| **GitHub**                             | Version control & portfolio showcase             |

---

## Dataset Information

* **Source:** Kaggle – *Superstore Sales Dataset*
* **Domain:** Retail / E-commerce
* **Data Includes:**

  * Orders
  * Customers
  * Products
  * Sales & Shipping details
  * Regions & Segments

---

## Project Architecture

```
Kaggle Dataset (CSV)
      ↓
Python (Data Cleaning & Feature Engineering)
      ↓
MS SQL Server (Star Schema & Queries)
      ↓
Power BI (Dashboards & Insights)
```

---

## Phase 1: Python – Data Preparation & Analysis

### Key Activities

* Loaded raw retail sales data
* Handled missing values and data inconsistencies
* Converted date columns and extracted time features
* Created derived columns:

  * Order Year, Month, Quarter
  * Shipping Days
  * Sales Category
  * Fast Shipping flag
* Performed Exploratory Data Analysis (EDA)
* Identified:
  * Top customers
  * Best & worst products
  * Regional sales patterns

### Output

* Cleaned dataset saved as CSV for SQL & Power BI

---

## Phase 2: MS SQL Server – Data Modeling & Analytics

### SQL Skills Demonstrated

* Table creation & constraints
* Business-driven SQL queries

### Sample Insights

* Top 10 customers by sales
* Monthly and yearly sales trends
* Running total of sales
* Shipping performance analysis
* Segment-wise sales contribution

---

## Phase 3: Power BI – Dashboarding & Reporting

### Dashboards Created

#### Executive Sales Overview

* Total Sales
* MTD / QTD / YTD Sales
* YOY Growth %
* Sales trends over time
---

## Key DAX Measures

* Total Sales
* MTD / QTD / YTD Sales
* Sales Last Year (LY)
* YOY Growth & YOY Growth %
* Top-N dynamic ranking

---

## Project Folder Structure

```
Retail_Sales_Analytics/
│
├── Python/
│   └── data_cleaning_analysis.ipynb
│
├── SQL/
│   └── star_schema_and_queries.sql
│
├── PowerBI/
│   └── retail_sales_dashboard.pbix
│
└── README.md
```

## Key Insights Generated

* Identified high-value customers driving majority of revenue
* Discovered seasonal sales trends using YOY analysis
* Analyzed shipping efficiency and its business impact

---

## Resume-Ready Description

> Built an end-to-end Retail Sales Analytics solution using Python, MS SQL Server, and Power BI. Cleaned and transformed raw data using Pandas, designed a star schema in SQL, and developed interactive dashboards with DAX time intelligence, YOY growth analysis, dynamic Top-N insights, drillthrough, and row-level security.

---

## Future Enhancements

* Automate data refresh using Power BI Service
* Add forecasting using Power BI analytics
* Integrate customer lifetime value (CLV) modeling
* Enhance dashboards with bookmarks and advanced tooltips

---

## Contact

**Author:** Venkatesh Metan
**Role:** Aspiring Data Analyst
**Skills:** Python | SQL | Power BI | Data Analytics

---

⭐ *If you found this project helpful, feel free to star the repository!*
