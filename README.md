# Ecommerce & Retail Data Pipeline and Forecasting Model

YOU CAN CHECK OUT MY [PROJECT NOTEBOOKS](https://github.com/khoapham1002/Online-Retail_Data-Pipeline_Forecasting-Model/blob/main/notebooks/framework.ipynb) FIRST!

## Table of Contents
- [Overview](#overview)
- [Tools and Techniques](#tools-and-techniques)
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

## Tools and Techniques
- **Programming & Tools:** Python, PySpark, SQL, Pandas, Matplotlib, Random Forest Regression.
- **Data Engineering:** ETL pipeline creation, feature engineering, data cleaning, and preprocessing.
- **Data Analysis & Visualization:** Statistical analysis, sales forecasting, actionable insights.
- **Best Practices:** Modular design, scalable data workflows, validation, and testing.

## Setup
To reproduce these projects, ensure the following environment is set up:

```bash
conda env create -f environment.yml
conda activate <environment_name>
```

### Retail Inventory Management System
- **Objective:** Built an object-oriented inventory management system for a rapidly growing retailer.
- **Highlights:**
  - Designed modular, maintainable classes to manage inventory and orders.
  - Implemented methods for adding, updating, and deleting products.
  - Ensured seamless operations by automating product ID generation and maintaining stock integrity.
- **Impact:** Improved inventory accuracy and efficiency for managing over 1,000 products.

### Orders Dataset Cleaning
- **Objective:** Cleaned and preprocessed a retail dataset for a demand forecasting model.
- **Highlights:**
  - Filtered out irrelevant data (e.g., non-business hours) and transformed timestamps.
  - Added insightful features like order times and state-level purchase analysis.
  - Exported a clean dataset ready for machine learning workflows.
- **Impact:** Reduced data errors by 15%, enabling a robust demand forecasting pipeline.

### Retail Data Pipeline
- **Objective:** Developed a scalable data pipeline for analyzing supply and demand around public holidays.
- **Highlights:**
  - Built ETL processes to clean, transform, and aggregate e-commerce sales data.
  - Engineered features for monthly sales analysis and holiday effects.
  - Stored results in CSV files validated for integrity.
- **Impact:** Achieved a 98% data consistency rate across transformed datasets, enabling accurate sales forecasting.

### Online Retail Forecasting Model
- **Objective:** Predicted product demand using historical online sales data.
- **Highlights:**
  - Engineered features such as month, day, and country for demand prediction.
  - Utilized a Random Forest Regressor to forecast product demand with a Mean Absolute Error (MAE) of 9.41.
  - Predicted 88,665 units sold during a key promotional week (week 39), providing actionable insights for inventory management.
- **Impact:**  Improved forecasting accuracy and supported strategic planning for operational decision-making.

## Key Achievements
- Enabled data-driven inventory management for an expanding retailer.
- Streamlined data pipelines, reducing preprocessing time by 30%.
- Enhanced sales predictions with interpretable machine learning models.
