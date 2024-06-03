# Amazon-Sales-Data
![Dashboard 1 (5)](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/7d9b004e-2b1a-48cd-835e-5a53793ce3a0)

## Problem Statement:
Sales management has gained importance to meet increasing competition and the
need for improved methods of distribution to reduce cost and to increase profits. Sales
management today is the most important function in a commercial and business
enterprise.

## Objective: 
Provide an overview of sales performance, identify trends, and highlight key insights to inform business decisions

## Project Overview

### 1. Data Cleaning, 
### 2. EDA (Exploratory Data Analysis)
### 3. Analysis 
### 4. Visualization
### 5. Key Insights
### 6. Recommendations for Future Analysis or Actions



## 1. Data Cleaning and Preprocessing

### Dataset columns: Region, Country, Item Type, Sales Channel, Order Priority, Order Date, Order ID, Ship Date, Units Sold, Unit Price, Unit Cost, Total Revenue, Total Cost, Total Profit.

### Key Steps:
#### Handled missing values and removed duplicates.
#### Ensured correct date formats.
#### Normalized categorical data.

### Key Questions:
#### Overall sales trends month-wise?
#### Year-wise sales trends?
#### Comparison of sales for the same month across different years?
#### Peak sales periods?
#### Patterns or anomalies in sales data?

## 2. Exploratory Data Analysis (EDA)

### A. Key metrics :
###        OrderID    Units Sold  Unit Price  Unit Cost   Total Revenue  
### count  1.000000   100.000000  100.000000  100.000000   1.000000 
### mean   5.550204  5128.710000  276.761300  191.048000   1.373488   
### std    2.606153  2794.484562  235.592241  188.208181   1.460029  
### min    1.146066   124.000000    9.330000    6.920000   4.870260   
### 25%    3.389225 2836.250000   81.730000   35.840000   2.687212  
### 50%    5.577086  5382.500000  179.880000  107.275000   7.523144  
### 75%    7.907551  7369.000000  437.200000  263.330000   2.212045 
### max    9.940222  9925.000000  668.270000  524.960000   5.997055 

### B. Distribution of Units Sold :
Bell curve with 0-10000 units sold range
![download](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/d23d712c-f15f-4db5-bc34-6ed5cb5615b9)

### C. Monthly Sales Trend :
Peak at July 2013
![download (1)](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/9fd9cc68-a2e7-40c2-9c84-4d17b4f19f2a)



## 3. Analysis & Visualization

### A. monthly sales trend analysis
Monthly sales and profit data
![Dashboard 1 (4)](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/b1cd0d99-17cc-4c09-a5ea-2a3161df746d)

### B. Yearly Sales Trend
Yearly sales and profit data
![2](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/aef6682e-7d8c-4c95-93ad-c4dbef0a3fe1)

### C. Peak Sales Periods
Top 5 peak sales months
![6](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/e17353d9-27a7-456f-9ce3-6187deb09a81)

### D. Region Sales and Profit Trend
![3](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/73244df1-0b4a-4825-a1a6-7d149243849f)

### E. Sales Performance by Region and Country
Revenue and profit by region and country
![4](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/6fa245b9-072d-4e6a-ba4f-6748636d3801)

### F. Sales By Country
![5](https://github.com/kaifahmed2002/Amazon-Sales-Data/assets/92524691/b1c4cd6f-2127-4a5d-90be-a5924787d381)

## 5. Key Insights 

### Data Quality and Distribution:

The dataset contains 100 records, and the average units sold are 5128.71.
The distribution of units sold follows a bell curve, indicating a normal distribution with most sales ranging from 0 to 10,000 units.
Average total revenue is approximately $1,373,488, and average total profit is around $441,682.

### Monthly Sales Trends:

Sales and profit show a significant peak in July 2013, indicating a high sales period.
Other notable peaks in sales include February 2017, February 2012, October 2010, and November 2011.

### Yearly Sales Trends:

The highest revenue was recorded in 2012, followed by 2010 and 2013.
Sales and profit declined after 2012 but showed occasional peaks in subsequent years.

### Regional Sales Performance:

Central America (Honduras), Asia (Myanmar, Turkmenistan), and Sub-Saharan Africa (Djibouti) are top-performing regions in terms of both total revenue and profit.
Countries like Honduras, Myanmar, and Djibouti have the highest sales figures, making them key markets.

### Country-wise Performance:

Top-performing countries include Honduras, Myanmar, and Djibouti, which have generated substantial revenue and profit.
The performance of these countries suggests strong market potential and opportunities for further growth.


## 6. Recommendations for Future Analysis or Actions

### Focus on Peak Sales Periods:

Leverage marketing and promotional activities around identified peak sales periods (e.g., July 2013, February 2017) to maximize sales.
Analyze factors contributing to high sales during these periods to replicate success.

### Regional and Country-Specific Strategies:

Develop targeted strategies for high-performing regions and countries, such as Central America, Asia, and Sub-Saharan Africa.
Invest in market research to understand customer preferences and demand drivers in top countries like Honduras, Myanmar, and Djibouti.

### Trend Analysis:

Conduct a deeper analysis of monthly and yearly trends to identify any underlying patterns or seasonal effects.
Use time-series forecasting methods to predict future sales trends and prepare accordingly.

## Try Dynamic Dashboard 👇
https://public.tableau.com/views/UnifiedMentorP1/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link



