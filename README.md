# Smart Inventory and Sales Optimization

A comprehensive data analytics project focused on beverage sales optimization and inventory management using advanced analytics, machine learning, and interactive dashboards.

## 📊 Project Overview

This project analyzes a large-scale beverage sales dataset containing over 1 million records to provide insights into sales patterns, vendor performance, and inventory optimization strategies. The analysis spans multiple years of sales data across various beverage categories and vendors.

## 🎯 Key Objectives

- **Sales Performance Analysis**: Identify top-performing products, vendors, and regions
- **Inventory Optimization**: Develop forecasting models for demand prediction
- **Geographic Analysis**: Analyze sales patterns across different counties and regions
- **Vendor Performance**: Evaluate vendor effectiveness and market share
- **Interactive Dashboard**: Create Power BI visualizations for business insights

## 📁 Project Structure

```
DataQuest/
├── 📊 Analysis.ipynb              # Main data analysis and cleaning
├── 📈 Analysis 1.ipynb            # Data preprocessing and geocoding
├── 🤖 Untitled.ipynb              # Time series forecasting models
└──📋 Sales Analytics Dashboard.pbix  # Power BI interactive dashboard
```

## 🔍 Dataset Overview

The project uses a comprehensive beverage sales dataset with the following key features:

- **Size**: Over 1 million records
- **Time Period**: Multiple years of sales data
- **Geographic Coverage**: US-based sales data with county-level granularity
- **Key Variables**:
  - Invoice/Item Number
  - Date, Store Information
  - Category and Product Details
  - Vendor Information
  - Sales Metrics (Bottles Sold, Revenue, Volume)
  - Geographic Data (County, Store Location)

## 🛠️ Technical Stack

### Data Analysis & Processing
- **Python 3.x**
- **Pandas**: Data manipulation and cleaning
- **NumPy**: Numerical computations
- **Matplotlib/Seaborn**: Data visualization
- **Dateutil**: Date parsing and manipulation
- **Pgeocode**: Geographic data processing

### Machine Learning & Forecasting
- **Statsmodels**: Time series analysis
- **Scikit-learn**: Machine learning metrics
- **Exponential Smoothing**: Demand forecasting models

### Visualization & Dashboard
- **Power BI**: Interactive business intelligence dashboard
- **Matplotlib**: Statistical plots and charts

## 📈 Key Findings & Insights

### 1. Sales Performance Analysis
- **Top Beverage Categories**: Citrus Burst, Citrus Cooler, Lavender Lemonade, Lemonade
- **Vendor Performance**: SAZERAC COMPANY INC leads in Vanilla Shake sales
- **Geographic Insights**: Madurai county shows significant sales volume (207,575 bottles)

### 2. Time Series Analysis
- **Seasonal Patterns**: Identified quarterly and monthly sales trends
- **Forecasting Models**: Implemented multiple Exponential Smoothing models
- **Stationarity**: Conducted ADF tests for time series analysis

### 3. Product Performance
- **Chai Latte Trends**: Analyzed year-over-year sales performance
- **Grape Splash**: Monthly sales trend analysis for 2018
- **Coconut Water**: Quarterly performance analysis

## 📊 Dashboard Features

The Power BI dashboard includes:
- **Sales Performance Metrics**
- **Geographic Sales Distribution**
- **Vendor Performance Analysis**
- **Product Category Insights**
- **Time Series Trends**
- **Interactive Filters and Drill-downs**

## 📸 Dashboard Screenshots

### Screenshot 1: Sales Overview Dashboard
![Dashboard 1](Dashboard%1.png)

### Screenshot 2: Geographic Analysis
![Dashboard 2](Dashboard%2.png)

### Screenshot 3: Vendor Performance
![Dashboard 3](Dashboard%3.png)



