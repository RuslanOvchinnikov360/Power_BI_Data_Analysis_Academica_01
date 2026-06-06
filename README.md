# Power BI Sales Analytics Dashboard

## Project Overview
This project is a Power BI sales analytics report developed as part of a business intelligence learning case. The goal was to clean and normalize raw data, build a data model, calculate key business metrics using DAX, and create an interactive sales performance dashboard.

## Data Source
The source data was provided in Excel format and contained sales transactions and reference tables.
Processed data volume:
* 730 sales records
* 571 unique orders
* 173 active customers
* 445 products
* 6 regions
* 4 customer segments
* 3 product categories
* 2 delivery methods
* Analysis period: 01.01.2022 - 29.04.2022

## Data Preparation
Data preparation was performed in Power Query:
* Removed empty and unnecessary rows
* Corrected data types
* Cleaned sales, profit and date fields
* Prepared fact and reference tables
* Connected tables in the data model

## Key Metrics
The following DAX measures were created:
* Revenue
* Profit
* Profitability %
* Active Customer Base
* Average Check
* Logistics Costs
* Negative-Profit Orders

Final dashboard results:
* Revenue: 1.10M
* Profit: 253.78K
* Profitability: 23.13%
* Active Customer Base: 173 customers
* Average Check: 1.92K
* Logistics Costs: 4,405
* Negative-Profit Orders: 278

## Dashboard Features
The report includes:
* KPI cards for key business indicators
* Sales dynamics by month
* Customer segment analysis
* Product and nomenclature analysis
* Geographic distribution map
* ABC analysis table
* Manager table showing negative-profit sales and number of affected orders

## Tools and Skills Used
* Power BI Desktop
* Power Query
* DAX
* Data Modeling
* Excel Data Preparation
* Dashboard Design
* Business Intelligence
* Sales Analytics
