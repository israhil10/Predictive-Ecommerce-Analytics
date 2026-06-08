# Predictive Ecommerce Analytics

## Quick Links

* 📊 [View Screenshots](#screenshots)
* 📈 [Key Insights](#key-insights)
* 🔮 [Predictive Analytics](#predictive-analytics)
* 🗂️ [Project Structure](#project-structure)
* 📬 [Contact](#contact)

---

## Table of Contents

* [Project Overview](#project-overview)
* [Business Problem](#business-problem)
* [Objectives](#objectives)
* [Dataset Description](#dataset-description)
* [Tools and Technologies](#tools-and-technologies)
* [Project Workflow](#project-workflow)
* [Customer Experience Analysis](#customer-experience-analysis)
* [Product Intelligence Analysis](#product-intelligence-analysis)
* [Seller Intelligence Analysis](#seller-intelligence-analysis)
* [Geographic Analysis](#geographic-analysis)
* [Revenue Trend Analysis](#revenue-trend-analysis)
* [Predictive Analytics](#predictive-analytics)
* [Key Insights](#key-insights)
* [Business Impact](#business-impact)
* [Challenges Faced](#challenges-faced)
* [Key Learnings](#key-learnings)
* [Project Structure](#project-structure)
* [Screenshots](#screenshots)
* [Contact](#contact)

---

## Project Overview

Predictive Ecommerce Analytics is an end-to-end Python data analytics project that analyzes customer behavior, delivery performance, product categories, seller contribution, geographic demand patterns, and future revenue growth within an e-commerce marketplace.

The project combines exploratory data analysis, advanced business intelligence visualizations, 3D analytics, dashboard development, and machine learning forecasting to generate actionable business insights.

The analysis is divided into five major business domains:

* Customer Experience Analytics
* Product Intelligence Analytics
* Seller Intelligence Analytics
* Geographic Intelligence Analytics
* Revenue Forecasting Analytics

---

## Business Problem

E-commerce companies generate massive amounts of transactional data but often struggle to convert that data into actionable business decisions.

Businesses need to:

* Improve customer satisfaction
* Optimize delivery performance
* Identify high-value product categories
* Recognize top-performing sellers
* Understand regional demand patterns
* Forecast future marketplace revenue

This project addresses these challenges through data-driven analytics and predictive modeling.

---

## Objectives

* Analyze customer satisfaction trends
* Measure the impact of delivery performance on review scores
* Identify revenue-driving product categories
* Evaluate seller contribution and concentration
* Discover geographic revenue opportunities
* Analyze monthly revenue growth trends
* Forecast future revenue using machine learning
* Build an executive-level analytics dashboard

---

## Dataset Description

* **Domain:** E-Commerce
* **Dataset:** Brazilian E-Commerce Public Dataset (Olist)
* **Records:** ~100,000 Orders
* **Level:** Transaction-Level Marketplace Data

### Key Tables

* Orders
* Customers
* Order Items
* Products
* Payments
* Reviews
* Sellers
* Geolocation Data

---

## Tools and Technologies

### Python

* Pandas
* NumPy

### Data Visualization

* Plotly
* Plotly Express
* Matplotlib

### Machine Learning

* Scikit-Learn
* Linear Regression

### Dashboard Development

* Dash

### Environment

* Jupyter Notebook

---

## Project Workflow

1. Data Cleaning and Preparation
2. Data Integration and Feature Engineering
3. Exploratory Data Analysis
4. Customer Experience Analytics
5. Product Intelligence Analytics
6. Seller Intelligence Analytics
7. Geographic Analytics
8. Revenue Trend Analysis
9. Revenue Forecasting
10. Dashboard Development

---

## Customer Experience Analysis

Customer experience analytics focuses on understanding how delivery performance impacts customer satisfaction.

### Key Metrics

* Delivery Days
* Delivery Delay Days
* Review Scores
* Delivery Performance Categories

### Business Finding

Customer satisfaction decreases significantly when deliveries are delayed. Early and on-time deliveries consistently receive higher review scores.

---

## Product Intelligence Analysis

Product analytics identifies high-performing categories and premium segments.

### Key Metrics

* Revenue by Category
* Units Sold
* Average Revenue per Unit
* Category Positioning

### Business Finding

Several categories generate premium revenue despite lower sales volumes, indicating strong pricing power and niche demand.

---

## Seller Intelligence Analysis

Seller analytics evaluates revenue concentration and marketplace contribution.

### Key Metrics

* Seller Revenue
* Orders Processed
* Products Sold
* Revenue Concentration

### Business Finding

A relatively small group of sellers contributes a disproportionate share of total marketplace revenue.

---

## Geographic Analysis

Geographic analytics explores regional demand and revenue generation patterns.

### Key Metrics

* Revenue by State
* Orders by State
* Revenue per Order by State

### Business Finding

A small number of states account for the majority of marketplace revenue and orders, revealing strong regional concentration.

---

## Revenue Trend Analysis

Historical revenue performance was analyzed using monthly revenue aggregation and moving average smoothing techniques.

### Business Finding

Marketplace revenue shows strong growth momentum with increasing revenue trends over time.

---

## Predictive Analytics

A Linear Regression model was developed to forecast future marketplace revenue.

### Forecasting Workflow

* Monthly Revenue Aggregation
* Time Index Feature Engineering
* Linear Regression Training
* Future Revenue Prediction

### Outcome

The forecasting model predicts continued revenue growth based on historical marketplace performance.

---

## Key Insights

### Customer Experience

* Delivery delays significantly reduce review scores.
* Early deliveries achieve the highest customer satisfaction.

### Product Intelligence

* Product performance varies significantly across categories.
* Premium categories generate strong revenue despite lower sales volume.

### Seller Intelligence

* Revenue generation is concentrated among a limited number of sellers.
* Top sellers dominate marketplace performance.

### Geographic Intelligence

* Revenue and order volumes are concentrated within a few states.
* Regional demand patterns create expansion opportunities.

### Revenue Forecasting

* Historical trends indicate sustainable marketplace growth.
* Revenue forecasting suggests continued future expansion.

---

## Business Impact

This project helps businesses:

* Improve customer satisfaction strategies
* Optimize delivery operations
* Identify profitable product categories
* Recognize high-performing sellers
* Target high-value geographic markets
* Support forecasting and budgeting decisions
* Enable data-driven strategic planning

---

## Challenges Faced

* Integrating multiple datasets into a unified model
* Managing missing and inconsistent data
* Designing meaningful business metrics
* Building advanced interactive visualizations
* Creating interpretable forecasting models

---

## Key Learnings

* End-to-end analytics workflow
* Data cleaning and feature engineering
* Business intelligence analysis
* Advanced Plotly visualizations
* 3D analytical visualizations
* Dashboard development using Dash
* Revenue forecasting using Machine Learning

---

## Project Structure

```text
├── data/
├── images/
├── notebooks/
│   └── Predictive E-Commerce Analytics.ipynb
├── dashboard/
│   └── app.py
├── requirements.txt
└── README.md
```

---

## Screenshots

### Dashboard Overview

![Dashboard](images/Dashboard%201.png)

### Dashboard KPI View

![Dashboard KPI](images/Dashboard%201.1.png)

### Dashboard Revenue View

![Dashboard Revenue](images/Dashboard%201.2.png)

### Customer Satisfaction vs Delivery Performance

![Customer Satisfaction](images/Customer%20Satisfaction%20vs%20Delivery%20Performance.png)

### Average Review Score by Delivery Group

![Review Score](images/Average%20Review%20Score%20by%20Delivery%20Group.png)

### Customer Experience Correlation Heatmap

![Heatmap](images/Customer%20Experience%20Correlation%20Heatmap.png)

### Category Intelligence Matrix

![Category Intelligence](images/Category%20Intelligence%20matrix.png)

### Premium Category Analysis

![Premium Category](images/Premium%20Category%20Analysis.png)

### Seller Performance Analysis

![Seller Performance](images/Seller%20Performance.png)

### Revenue by States

![Revenue by States](images/Revenue%20by%20States.png)

### Orders by State

![Orders by State](images/Orders%20by%20State.png)

### Revenue per Order by State

![Revenue per Order](images/Revenue%20per%20Order%20by%20states.png)

### Monthly Revenue Trend

![Monthly Revenue](images/Monthly%20Revenue%20Trend.png)

### Revenue Trend and Moving Average

![Moving Average](images/Revenue%20trend%20and%20moving%20average.png)

### Revenue Forecast Using Linear Regression

![Revenue Forecast](images/Revenue%20Trend%20Forcast%20using%20Linear%20regression.png)

---

## Contact

**Name:** Shaikh Mohd Israhil

**Email:** [mohdisrahils@gmail.com](mailto:mohdisrahils@gmail.com)

**LinkedIn:** https://www.linkedin.com/in/mohd-israhil-shaikh-3b8b04281/

**GitHub:** https://github.com/israhil10
