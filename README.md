# Automotive Spare Parts Sales Analysis

**An Excel-Based Data Analytics Portfolio Project**

## Project Overview

This project focuses on analyzing historical sales transaction data from an automotive spare parts store using Microsoft Excel.

The analysis aims to evaluate sales performance, identify top-performing products, understand transaction patterns, and generate business insights to support better sales and inventory management decisions.


# Executive Summary

## Automotive Spare Parts Sales Analysis

This project analyzes automotive spare parts sales data to identify sales performance trends, evaluate product performance, and generate business insights to support better business decisions.

Using Microsoft Excel, the analysis covers 10,418 sales records from October to December 2019.

### Key Performance Indicators

- **Total Revenue:** Rp2,137,397,166
- **Total Transactions:** 4,174
- **Total Quantity Sold:** 19,120 units
- **Average Transaction Value (ATV):** Rp512,074.07
- **Average Selling Price (ASP):** Rp111,788.55

### Key Findings

- October recorded the highest monthly revenue at Rp753.49 million.
- Total transactions increased consistently from October to December, while revenue experienced fluctuations.
- KAIN KOPLING (CLUTCH DISC) generated the highest product revenue at Rp74.05 million.
- TERMINAL GEPENG recorded the highest sales volume with 500 units sold.
- The top 10 revenue-generating products contributed 15.53% of total revenue.

### Business Recommendations

- Monitor inventory levels of high-volume products to minimize stockout risks.
- Evaluate product sales performance to support purchasing decisions.
- Monitor monthly revenue and transaction trends to identify changes in sales performance.
- Improve product data completeness to support more accurate sales reporting and analysis.

### Tools Used

- Microsoft Excel
- PivotTables
- Excel Formulas
- Data Cleaning and Validation
- Data Visualization

## Business Background

An automotive spare parts store manages various products with different sales volumes and demand patterns. Understanding these patterns is important for monitoring business performance and supporting effective inventory management.

Through data analysis, this project aims to transform historical sales data into meaningful insights that can help support business decisions.

## Project Objectives

The main objectives of this project are:

1. Analyze sales revenue performance over time.
2. Identify products with the highest revenue contribution.
3. Identify the best-selling products based on sales quantity.
4. Analyze transaction volume and average transaction value.
5. Identify opportunities to improve inventory management.

## Business Questions

This project will address the following business questions:

| No. | Business Question |
|---|---|
| 1 | How does sales revenue change over time? |
| 2 | Which products generate the highest revenue? |
| 3 | Which products have the highest sales quantity? |
| 4 | How does the number of transactions change over time? |
| 5 | What is the average transaction value? |
| 6 | What sales patterns can support better inventory decisions? |

## Key Performance Indicators (KPIs)

| KPI | Formula |
|---|---|
| Total Revenue | Quantity × Selling Price |
| Total Transactions | Count of unique invoices |
| Total Quantity Sold | Sum of quantity |
| Average Transaction Value (ATV) | Total Revenue / Total Transactions |
| Average Selling Price (ASP) | Total Revenue / Total Quantity Sold |

## Tools & Technologies

- Microsoft Excel
- Excel Formulas
- Excel PivotTables
- Data Cleaning
- Data Analysis
- Data Visualization

## Project Scope

The project focuses on historical sales transaction data from an automotive spare parts store.

The analysis covers:

- Sales revenue performance
- Transaction trends
- Product sales performance
- Sales quantity patterns
- Inventory-related business insights

## Expected Deliverables

- Data quality assessment
- Cleaned sales dataset
- Sales performance analysis
- Product performance analysis
- Interactive Excel dashboard
- Business insights and recommendations


## Duplicate Check

A duplicate check was performed across the 12 transaction fields.

The analysis identified 4 potentially duplicate records across 2 groups:

| Invoice ID | Product Name | Duplicate Records |
|---|---|---:|
| 120156 | AS KOPEL LUAR | 2 |
| 121098 | BOLA LAMPU | 2 |

These records were flagged for further validation. No records were removed during this stage to avoid accidentally deleting valid transactions.



## Missing Values Assessment

The data quality assessment identified missing and NULL values in several transaction fields.

| Column | Blank Cells | Text NULL | Total |
|---|---:|---:|---:|
| kd_barang | 3,289 | 0 | 3,289 |
| nama_barang | 17 | 0 | 17 |
| kode_mobil | 50 | 3,288 | 3,338 |
| merk | 50 | 3,288 | 3,338 |
| satuan | 0 | 3,309 | 3,309 |

These missing values may affect product identification, vehicle classification, and unit-level analysis. They will be considered during the data cleaning stage.


## Duplicate Handling

Two groups of potentially duplicated transaction records were identified during the data quality assessment.

Since the original transaction receipts were unavailable, these records were retained to avoid removing potentially valid transactions.

The duplicate status remains unverified and is considered a data quality limitation.



## Transaction Value Validation

The transaction value validation confirmed that all 10,418 records have consistent total values.

- Matching records: 10,418
- Mismatched records: 0

The validation confirms that the recorded transaction totals match the calculated values based on quantity multiplied by selling price.



## Date Format Validation

All 10,418 transaction records passed the date format validation.

The transaction date column contains valid Excel date values and is ready for time-based analysis.


## Dataset Time Period

The dataset covers sales transactions from October 2019 to December 2019.

This three-month period will be used as the scope of the sales performance analysis.


### Product Performance Insights

1. **Top Revenue-Generating Product**  
   KAIN KOPLING (CLUTCH DISC) generated the highest revenue, reaching Rp74.05 million, followed by MATAHARI (CLUTCH COVER) at Rp61.96 million.

2. **Highest Sales Volume**  
   TERMINAL GEPENG recorded the highest sales volume with 500 units sold, followed by BUSI with 447 units.

3. **Revenue vs. Sales Volume**  
   The products generating the highest revenue are not necessarily the products with the highest sales volume. This indicates differences in sales value across products.

4. **Top 10 Revenue Contribution**  
   The top 10 revenue-generating products contributed 15.53% of total revenue, indicating that revenue was distributed across a broader range of products.

### Business Recommendations

- Monitor stock availability for high-volume products to reduce the risk of stockouts.
- Evaluate pricing and sales performance of high-revenue products.
- Review product performance regularly to support purchasing and inventory planning.

## Project Status

**In Progress** — Currently working on project understanding and business objectives. Data auditing, cleaning, analysis, and dashboard development will follow.

---

*This project is developed as part of a Data Analyst portfolio to demonstrate practical data analysis skills using Microsoft Excel.*



