# Amazon Sales ETL Pipeline & Power BI Analytics

This project demonstrates an end-to-end data analytics workflow built using **Microsoft Fabric, Spark, Delta Lake, and Power BI**.  
The objective is to transform raw e-commerce transactional data into a structured analytical model and create interactive dashboards for business analysis.

The pipeline ingests a synthetic Amazon-style sales dataset, performs data cleaning and transformations, and builds a **star schema optimized for reporting and KPI analysis**.

## Dataset

The dataset used in this project is a synthetic Amazon-style e-commerce dataset containing **100,000 transactions** with information about:

- Orders
- Customers
- Products and brands
- Prices, taxes, discounts
- Payment methods
- Shipping and logistics
- Order status
- Geographic information

Source:  
https://www.kaggle.com/datasets/rohiteng/amazon-sales-dataset

## Project Overview

The project implements a **lakehouse architecture** where the data is progressively refined:

- **Bronze layer** – raw data ingestion  
- **Silver layer** – data cleaning and standardization  
- **Gold layer** – transformation into a star schema model for analytics  

The final model is used in **Power BI** to create interactive dashboards analyzing:

- Sales performance
- Customer behavior
- Seller performance
- Time-based growth metrics (YoY, MoM, AOV)

## Reports

Two Power BI reports were developed:

**Sales Report**
- Overview of total sales, orders, and trends
- Geographic sales analysis
- Order status monitoring
- Interactive filtering and drilldown

**Customer Report**
- Customer-level performance analysis
- Spending behavior
- Customer scoring system
- Dynamic filtering and drillthrough

## Documentation

A full explanation of the **ETL pipeline, data transformations, star schema design, DAX measures, and Power BI reports** is available in the project report included in this repository.