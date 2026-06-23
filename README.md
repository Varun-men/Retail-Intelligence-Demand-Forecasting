# Retail-Intelligence-Demand-Forecasting

## Overview

The Retail Intelligence & Demand Forecasting System is an end-to-end Data Science project designed to analyze retail sales data, identify business insights, and forecast product demand using Machine Learning.

The project integrates SQL, Data Analytics, Machine Learning, and Streamlit Deployment to provide an interactive business intelligence dashboard for retailers and analysts.

---

## Problem Statement

Retail businesses often struggle with:

* Inaccurate demand forecasting
* Overstocking and understocking
* Inefficient inventory planning
* Lack of actionable business insights

This project addresses these challenges by analyzing historical retail data and predicting future demand using machine learning models.

---

## Tech Stack

### Programming & Analytics

* Python
* Pandas
* NumPy

### Database

* MySQL
* SQLAlchemy
* PyMySQL

### Data Visualization

* Matplotlib
* Seaborn
* Plotly

### Machine Learning

* Scikit-Learn
* Random Forest Regressor
* Gradient Boosting Regressor

### Deployment

* Streamlit
* GitHub

---

## Dataset Information

The dataset contains retail product sales information including:

* Product Category
* Quantity Sold
* Unit Price
* Freight Cost
* Customer Count
* Product Ratings
* Product Weight
* Competitor Pricing
* Seasonal Factors
* Holiday Indicators

### Dataset Size

* Records: 676
* Features: 30+
* Product Categories: 9

---

## SQL Integration

The dataset was imported into MySQL for structured data storage and business analysis.

### Key SQL Operations

* Data Import from CSV to MySQL
* Category-wise Sales Analysis
* Revenue Analysis
* Monthly Demand Analysis
* Data Validation

---

## Exploratory Data Analysis (EDA)

Performed extensive EDA to understand business patterns.

### Key Analyses

* Data Quality Assessment
* Missing Value Analysis
* Demand Distribution Analysis
* Outlier Detection
* Correlation Analysis
* Category-wise Demand Analysis
* Revenue Analysis
* Price vs Demand Analysis
* Time Series Demand Trends

### Key Insights

* Health & Beauty generated the highest revenue.
* Garden Tools recorded the highest demand.
* Customer count strongly influenced demand.
* Freight cost significantly impacted sales.
* Product presentation (images) positively affected demand.

---

## Feature Engineering

Performed preprocessing and feature engineering:

* Removed data leakage features
* One-Hot Encoding of product categories
* Feature selection using correlation and importance analysis
* Dataset preparation for machine learning models

---

## Machine Learning Models

### 1. Random Forest Regressor

Performance:

* MAE: 6.08
* RMSE: 9.97
* R² Score: 0.634

### 2. Gradient Boosting Regressor (Final Model)

Performance:

* MAE: 5.99
* RMSE: 9.93
* R² Score: 0.636

The Gradient Boosting model was selected as the final model due to its superior predictive performance.

---

## Feature Importance

Top demand drivers identified by the model:

1. Seasonal Factor (s)
2. Customer Count
3. Freight Price
4. Product Weight
5. Product Photos
6. Competitor Pricing
7. Unit Price
8. Product Specifications

These insights help businesses make informed inventory and pricing decisions.

---

## Streamlit Dashboard

An interactive Streamlit dashboard was developed to visualize insights and predictions.

### Dashboard Features

* Project Overview
* Business Analytics Dashboard
* Demand Trend Visualization
* Category Analysis
* Revenue Insights
* Demand Prediction System
* Inventory Alert System
* Interactive Charts and KPIs

---

## Dashboard Screenshots

Example:


<img width="1852" height="896" alt="Dashboard" src="https://github.com/user-attachments/assets/2d7ab883-d921-4f75-9fa3-e878b2ad2464" />
<img width="1877" height="892" alt="Prediction" src="https://github.com/user-attachments/assets/c7eff534-6aa1-4088-9c03-703ef584b68b" />

---

## Project Structure

```text
Retail-Intelligence-Demand-Forecasting
│
├── app.py
├── eda.py
├── file.py
├── retail_engineered.csv
├── demand_forecasting_model.pkl
├── retail_price.csv
├── requirements.txt
├── README.md
│
├── screenshots/
```

---

## Future Improvements

* XGBoost Integration
* Time-Series Forecasting Models
* Real-Time Data Integration
* Automated Inventory Optimization
* Cloud Database Integration
* Advanced Business Intelligence Reports

---

## Author

**Varun Kumar**

B.Tech Computer Science Engineering
Delhi Technical Campus (GGSIPU)

### Connect With Me

* GitHub: https://github.com/Varun-men
* LinkedIn: www.linkedin.com/in/varunkumar76

---

## Project Outcome

This project demonstrates practical skills in:

* Data Analytics
* SQL
* Machine Learning
* Business Intelligence
* Data Visualization
* Dashboard Development
* Model Deployment

It serves as a complete end-to-end retail analytics solution capable of generating actionable business insights and forecasting product demand.

