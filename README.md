
# Logistic and shipment Analysis

## Table of Contents:
1. [Introduction and Motivation](#data)
2. [Data Loading and Cleaning](#cau2)
3. [Exploratory Data Analysis (EDA)](#cau4)
4. [Conclusion](#cau5)

<div id='data'/>
  
## 1. Introduction and Motivation

Driven by a passion for understanding data and creating visualizations to support supply chain and business decisions, this project focuses on interpreting a large logistics shipment dataset. It aims to enhance my technical skills in data cleaning, manipulation, and visualization while fostering critical thinking to draw meaningful conclusions about supply chain processes. This experience will strengthen my expertise in data-driven decision-making and contribute to my professional growth.

<div id='cau2'/>
  
  
## 2. Data Loading and Cleaning
  
The first step involves loading the sales data from different CSV file to Power Bi Desktop. The dataset undergoes cleaning processes to enhance its usability. Unrelated or blank columns in SalesPerson cloumn are dropped. Null values are handled by dropping rows or filling in missing information. Data types are adjusted, ensuring consistency, and columns like 'Date' are converted to datetime objects for better analysis.

<div id='cau4'/>

  
## 3.  Data Processing & Exploratory Data Analysis
**3.1 Analyze key logistics metrics**

I analyzed key metrics such as delivery times, revenue, and shipment types using Power BI DAX queries. I used cards to display the total number of shipments categorized as active, completed, or returned, along with their percentages of total shipments.

**3.2 Understand shipment trend**

I visualized shipment trends using a column chart that displayed data by month and year, enabled through a slicer. I created a calendar table and established relationships with existing tables to facilitate time-based analysis.

**3.3 Visualize revenue trend based on time**

I visualized shipment revenue using a slicer for time categories by month and year. I incorporated tooltips to display detailed information, including the date, revenue, and number of shipments for each month, highlighting March and May as the months with the highest revenue.

**3.4 Avg delivery time by geography**

A clustered bar chart visualizes delivery times across different countries, utilizing a color measure created with the SWITCH function in Power BI DAX to assign three distinct colors based on delivery length. The visualization highlights that Australia has the longest delivery time, while the USA has the shortest.

**3.5  Sales person analysis**

The project features a table that highlights each salesperson's active, completed, and returned shipments. A sparkline is also included to visualize their shipment trends over time.

**3.6 Revenue by category analysis**

A donut chart with target measurements illustrates revenue contributions by category, with each category's revenue percentage shown relative to 100%. Electronics emerges as the leading category, contributing 68% of the total revenue. Additionally, a card displays the total revenue across all categories for a comprehensive overview.

**3.7 Dashboard filters**

Filters for time, categories, and countries are applied to the entire dashboard to enhance visualization and allow for focused analysis. Consistent use of three primary colors—blue, pink, and green—ensures a clear and visually cohesive dashboard design.

<div id='cau5'/>
  
## 5. Conclusion
The Logistic and shipment project provides valuable insights into revenue by time, categories and person as well as number of different active, completed and returned shipments.This information can be leveraged by the company to identify seasonal patterns, high-performing product lines, and key customer segments. This knowledge enables targeted marketing efforts, resource allocation, and pricing strategies tailored to maximize profitability. Additionally, tracking the number of active, completed, and returned shipments allows businesses to evaluate the efficiency of their supply chain and fulfillment processes.
