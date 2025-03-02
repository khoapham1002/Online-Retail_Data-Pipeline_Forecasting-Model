# Ecommerce & Retail Data Pipeline and Forecasting Model

YOU CAN CHECK OUT MY [PROJECT NOTEBOOKS](https://github.com/khoapham1002/Online-Retail_Data-Pipeline_Forecasting-Model/blob/main/notebooks/framework.ipynb) FIRST!

## Table of Contents
- [Overview](#overview)
- [Setup](#setup)
- [Retail Inventory Management System](#retail-inventory-management-system)
- [Orders Dataset Cleaning](#orders-dataset-cleaning)
- [Retail Data Pipeline](#retail-data-pipeline)
- [Online Retail Forecasting Model](#online-retail-forecasting-model)
- [Key Achievements](#key-achievements)

## Overview   
Applied data science and engineering expertise to develop scalable, industry-grade solutions, enhancing business operations and decision-making with measurable impacts on efficiency and accuracy.

1. **Retail Inventory Management System:** Built an OOP-based system managing 1,000+ products, improving inventory accuracy and operational efficiency.
2. **Orders Dataset Cleaning:** Processed retail orders data for demand forecasting, reducing data errors by 15% and enabling robust insights.
3. **Retail Data Pipeline:** Designed scalable ETL workflows for holiday sales analysis, achieving 98% data consistency.
4. **Online Retail Forecasting Model:** Developed a Random Forest Regressor model to forecast product demand with 9.41 MAE, predicting 88,665 units sold in a promotional week, enabling precise inventory management and planning.



## Setup
To reproduce these projects, ensure the following environment is set up:

```bash
conda env create -f environment.yml
conda activate <environment_name>
```



## Retail Inventory Management System
### Tools & Technologies:
Python, Object-Oriented Programming (OOP)

### Project Overview:
Developed an OOP-based inventory management system for a growing online retailer to efficiently handle product creation, updates, deletions, and order placements.

### Key Contributions:
* Designed Product & Order classes with methods for adding, updating, and deleting products.
* Built an order placement system that updates product inventory dynamically.
* Implemented a class-level inventory tracking system to maintain product records.

### Impact & Insights:
* Streamlined inventory control and order processing for a scalable retail system.
* Improved code maintainability using OOP principles.




## Orders Dataset Cleaning for Demand Forecasting
### Tools & Technologies:
Python, PySpark

### Project Overview:
Cleaned and preprocessed orders data for an electronics e-commerce company to support machine learning-based demand forecasting.

### Key Contributions:
* Filtered orders: Removed transactions placed between 12 AM – 5 AM.
* Standardized product data: Converted names & categories to lowercase and removed discontinued items (TVs).
* Extracted state-level purchase data for regional insights.
* Optimized storage: Exported cleaned data to Parquet for efficient ML model training.

### Impact & Insights:
* Provided a clean dataset for accurate demand forecasting.
* Ensured data consistency for future predictive models.




## Retail Data Pipeline for Sales Analysis
### Tools & Technologies:
Python, Pandas, SQL, Data Pipelines

### Project Overview:
Developed a data pipeline to process Walmart sales and external factors (holidays, fuel prices, CPI, unemployment), enabling monthly sales analysis.

### Key Contributions:
* Extracted & merged grocery sales with external data sources.
* Cleaned and transformed data by handling missing values and filtering sales above $10,000.
* Aggregated monthly sales trends to analyze seasonal demand patterns.
* Saved processed data for business intelligence and forecasting.

### Impact & Insights:
* Enabled insightful sales trend analysis for supply chain planning.
* Created a structured dataset for further analytics and forecasting.




## Online Retail Forecasting Model
### Tools & Technologies:
PySpark, Machine Learning, Time Series Forecasting

### Project Overview:
Built a sales forecasting model for an e-commerce platform to predict future product demand, supporting inventory and promotional planning.

### Key Contributions:
* Processed transactional sales data, converting timestamps to structured date formats.
* Trained a Random Forest model to predict future sales based on historical trends.
* Achieved Mean Absolute Error (MAE) for evaluation.
* Forecasted sales for week 39 of 2011, estimating demand for promotions.

### Impact & Insights:
* Provided predictive insights to optimize stock availability.
* Enabled data-driven promotional planning for high-sales periods.
