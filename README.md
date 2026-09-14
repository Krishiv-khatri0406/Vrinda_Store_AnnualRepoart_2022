# 📊 Vrinda Store — E-Commerce Sales Analysis Using Excel

## 📌 Project Overview

This project analyses **Vrinda Store's 2022 e-commerce sales data** using Microsoft Excel to understand sales performance, customer behaviour, order trends, product performance, and geographic patterns.

The project follows an end-to-end analytical workflow:

**Raw Data → Data Validation & Transformation → Analysis → Visualization → Dashboard → Business Insights**

The objective was to transform a large transactional dataset into meaningful information that could help a business understand **where its sales are coming from, who its customers are, how sales change over time, and where opportunities for improvement may exist.**

---

## 🎯 Business Questions

The analysis focuses on questions such as:

* How are sales distributed across different months and quarters?
* Which customer demographic contributes the most revenue?
* What is the distribution of order statuses?
* Which states generate the highest sales?
* Which sales channels contribute the most revenue?
* How do different customer segments perform?
* What patterns can be identified from the transaction data?
* What actionable insights can be derived from the data?

---

## 🗂️ Dataset

The dataset contains approximately **31,000 transactional records** from Vrinda Store's 2022 sales activity.

Key fields include:

* Order ID
* Customer ID
* Gender
* Age
* Date
* Order Status
* Sales Channel
* SKU
* Category
* Size
* Quantity
* Amount
* Shipping City
* Shipping State
* Postal Code
* Country
* B2B indicator

The dataset contains multiple records for some Order IDs because individual orders can contain multiple line items.

> **Note:** The dataset is a publicly available/practice dataset and is used here for educational and portfolio purposes. The analysis, transformations, dashboard and insights were created as part of this project.

---

## 🧹 Data Preparation & Transformation

Before performing the analysis, the raw transactional data was prepared for analytical use.

The workflow included:

* Checking the structure and consistency of the dataset
* Validating data types and fields
* Creating calculated fields
* Creating **Age Group** categories
* Extracting **Month** from transaction dates
* Creating **Quarter** classifications
* Calculating sales-related metrics
* Structuring the data using an Excel Table
* Preparing the dataset for PivotTables and dashboard analysis

### Age Segmentation

Customers were grouped into:

* **Young Adult**
* **Adult**
* **Senior**

This segmentation was created to make demographic analysis easier and more meaningful.

---

## 📈 Analysis Performed

### 1. Monthly Sales Analysis

Monthly sales and quantity were analysed to identify:

* Sales trends throughout the year
* High-performing months
* Low-performing months
* Changes in sales volume over time

### 2. Quarterly Analysis

Sales were grouped into:

* Q1
* Q2
* Q3
* Q4

This provides a higher-level view of the store's yearly performance.

### 3. Customer Demographic Analysis

The project analyses sales across:

* Gender
* Age groups

This helps identify the customer segments contributing most significantly to sales.

### 4. Order Status Analysis

Order outcomes were analysed across:

* Delivered
* Cancelled
* Returned
* Refunded

This provides an overview of the store's order fulfilment performance.

### 5. Geographic Analysis

Sales were analysed across different Indian states to identify:

* High-performing markets
* Regional sales concentration
* Geographic opportunities

### 6. Sales Channel Analysis

The dataset contains multiple e-commerce channels, allowing sales performance to be examined across different platforms.

---

## 📊 Dashboard

The final Excel dashboard provides a visual summary of the analysis.

It includes visualizations covering:

* Sales trends
* Monthly performance
* Quarterly performance
* Customer gender distribution
* Order-status distribution
* Geographic performance

### Dashboard Preview

*Add your dashboard screenshot here.*

```text
![Vrinda Store Dashboard](images/dashboard.png)
```

---

## 🛠️ Tools & Skills Used

### Microsoft Excel

* Excel Tables
* PivotTables
* PivotCharts
* Excel formulas
* Conditional calculations
* Data transformation
* Data validation
* Data analysis
* Dashboard creation
* Data visualization

### Analytical Skills

* Exploratory Data Analysis
* Trend Analysis
* Customer Segmentation
* Geographic Analysis
* Sales Performance Analysis
* KPI Analysis
* Business-oriented interpretation of data

---

## 💡 Key Takeaways

The analysis demonstrates how transactional e-commerce data can be transformed into a structured analytical model and dashboard.

Some of the key areas investigated include:

* Monthly and quarterly sales performance
* Customer demographic contribution
* Order fulfilment outcomes
* Geographic sales distribution
* Sales-channel performance

The analysis can be used to identify high-performing customer segments and markets while also highlighting areas where order fulfilment and channel performance may require further investigation.

---

## 📌 Project Structure

```text
Vrinda-Store-Sales-Analysis/
│
├── README.md
│
├── data/
│   └── Vrinda_Store_Raw_Data.xlsx
│
├── analysis/
│   └── Vrinda_Store_Annual_Report_2022.xlsx
│
└── images/
    └── dashboard.png
```

---

## 🚀 Future Improvements

This project can be extended beyond Excel by:

* Recreating the analysis using **SQL**
* Performing deeper exploratory analysis using **Python**
* Building an interactive **Power BI dashboard**
* Performing customer retention and repeat-purchase analysis
* Comparing B2B and B2C performance
* Conducting more detailed sales-channel analysis
* Developing additional business KPIs

---

## 👨‍💻 About the Project

This project was created as part of my learning journey toward becoming a **Data Analyst**.

The goal was not only to create charts, but to understand the complete process of taking transactional data, preparing it for analysis, extracting meaningful patterns, and communicating those findings through an Excel dashboard.

**Tools:** Microsoft Excel
**Dataset:** Public/practice e-commerce dataset
**Project Type:** Data Analysis / Business Intelligence
**Year Analysed:** 2022
