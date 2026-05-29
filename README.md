# Retail Sales & Customer Analytics Dashboard

## Overview

This project is an interactive **Power BI dashboard** designed to analyze retail sales performance, customer behavior, product trends, and return rates using the AdventureWorks dataset.

The dashboard provides business insights into:

* Revenue & profit performance
* Customer analytics
* Product performance
* Return analysis
* Regional and category-based trends

This project demonstrates:

* Data modeling using Star Schema
* Data transformation with Power Query
* DAX calculations & KPIs
* Interactive dashboard design in Power BI

---

# Project Structure

```bash
powerBIproject/
│
├── Project_.pbix
├── dataset_adventurework2.zip
├── README.md
```

---

# Naming Conventions

## File Naming

* Use lowercase for dataset files
* Use PascalCase for Power BI tables
* Use meaningful and readable names

Examples:

```bash
dataset_adventurework2.zip
Project_.pbix
```

---

## Table Naming

### Fact Tables

Use prefix:

```bash
Fact
```

Examples:

```bash
FactSales
FactReturns
```

### Dimension Tables

Use prefix:

```bash
Dim
```

Examples:

```bash
DimCustomer
DimDate
DimProduct
DimTerritory
```

### Measure Tables

```bash
Measure Table
```

---

## Column Naming

Use PascalCase:

```bash
CustomerKey
ProductName
OrderQuantity
ReturnRate
```

Avoid:

```bash
customer_key
product-name
```

---

# Dashboard Pages

## 1. Executive Dashboard

* Revenue trending
* Total profit
* Orders analysis
* Return rate monitoring
* Top products

## 2. Product Detail Dashboard

* Product KPI tracking
* Monthly trends
* Profit adjustment simulation
* Product metric selection

## 3. Customer Detail Dashboard

* Customer segmentation
* Revenue per customer
* Occupation & income analysis
* Top customer ranking

## 4. Map Dashboard

* Territory-based sales analysis
* Geographic visualization

---

# Dataset

The project uses the AdventureWorks Retail Dataset.

Included data:

* Sales Data
* Customer Lookup
* Product Lookup
* Territory Lookup
* Returns Data
* Calendar Table

---

# Technologies Used

* Microsoft Power BI
* Power Query
* DAX
* Star Schema Modeling

---

# Key KPIs

## Sales Metrics

* Total Revenue
* Total Orders
* Monthly Revenue Growth
* Return Rate

## Customer Metrics

* Total Customers
* Revenue Per Customer

## Product Metrics

* Product Profitability
* Product Return %
* Top Ordered Products

---

# Git Commands

## Clone Repository

```bash
git clone https://github.com/vietsosad/powerBIproject.git
```

---

## Move Into Project Folder

```bash
cd powerBIproject
```

---

## Add Files

```bash
git add .
```

Or add a specific file:

```bash
git add Project_.pbix
git add dataset_adventurework2.zip
```

---

## Commit Changes

```bash
git commit -m "update dashboard"
```

Examples:

```bash
git commit -m "upload pbix file"
git commit -m "add retail dataset"
git commit -m "update customer dashboard"
```

---

## Push To GitHub

```bash
git push origin main
```

---

# How To Use

## Step 1

Download or clone the repository.

## Step 2

Extract:

```bash
dataset_adventurework2.zip
```

## Step 3

Open:

```bash
Project_.pbix
```

using Power BI Desktop.

## Step 4

Refresh data if needed:

* Transform Data
* Update file paths
* Click Refresh

---

# Business Insights Generated

* Identified top-performing product categories
* Analyzed customer purchasing behavior
* Monitored product return rates
* Evaluated monthly revenue trends
* Compared customer segments by income & occupation

---

# Future Improvements

* Add forecasting models
* Add RFM customer segmentation
* Deploy dashboard to Power BI Service
* Add real-time refresh
* Improve mobile responsiveness

---

# Author

## Việt Lê

Power BI Developer & Data Analytics Enthusiast

GitHub:
https://github.com/vietsosad/powerBIproject
