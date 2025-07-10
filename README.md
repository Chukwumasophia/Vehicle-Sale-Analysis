# 🚘 Vehicle Sales Analysis Project

## 📑Table of Contents

1. [Project Overview](project-overview)  
2. [Problem Statement](problem-statement)  
3. [Dataset Overview](dataset-overview)  
4. [Objective](objective)  
5. [Data Cleaning and Modeling](data-cleaning-and-modeling)  
6. [Tools Used](tools-used)  
7. [Customer and Product Dashboard Analysis](customer-and-product-dashboard-analysis)  
8. [Geography and Time Series Dashboard](geography-and-time-series-dashboard)  
9. [Methodology](methodology)  
10. [Findings and Analysis](findings-and-analysis)  
11. [Recommendations](recommendations)



## Project Overview

This project presents a deep dive into vehicle sales data using Excel. The goal is to create an interactive report that helps stakeholders understand revenue distribution, top-performing products and customers, regional performance, and time-based sales trends — all aimed at driving better decision-making.


## 2. 📌 Problem Statement

With hundreds of products sold across various countries and territories, there is a need to analyze the vehicle sales data to uncover patterns in customer purchasing behavior, product demand, and regional performance. This project helps business teams to identify high-value customers, optimize inventory, and enhance sales strategies.


## 3. 📂 Dataset Overview

- **File**: `Vehicle Sales Project.xlsx`  
- **Source**: Simulated real-world dataset  
- **Records**: ~1,200+ rows  
- **Columns**: 24 columns  
- **Key Fields**: Product Category, Quantity Sold, Revenue, Deal Size, Product Code, Year, Month, Territory, Country, Customer Name


## 4. 🎯 Objective

- Identify top-selling products and customer revenue contributions  
- Measure performance by region, deal size, and product category  
- Analyze monthly and quarterly trends  
- Use dashboards to communicate insights visually


## 5. 🧹 Data Cleaning and Modeling

- Removed unnecessary columns (e.g., Address Line 2)  
- Renamed columns for clarity  
- Filled missing values:  
  - `State` → "Unknown"  
  - `Postal Code` → "00000"  
- Removed duplicates  
- Built 4 core tables:  
  - **Fact Table**: Vehicle Sales  
  - **Dim Customer**  
  - **Dim Product**  
  - **Dim Geography**


## 6. 🛠 Tools Used

- Microsoft Excel  
- Power Pivot  
- PivotTables  
- DAX Functions  
- Slicers  
- Custom Icons & Shapes  
- Map Visualization


## 7. 👥 Customer and Product Dashboard Analysis

**Key Insights:**
- **Top Customer**: Euro Shopping Channel ($236,798.17)  
- **Highest Deal Size**: Medium Deals ($1,039,362.62)  
- **Top Product**: Classic Cars ($672,573.28)  
- **Top Customers by Revenue** visualized using bar charts  
- Product category sales volumes and revenue breakdown included  
- Customer volume by country (Top 5)

 # CUSTOMER AND PRODUCT DASHBOARD 
![Screenshot 2025-07-09 123917](https://github.com/user-attachments/assets/44bf7c14-5b2b-458d-b122-9c56c4cf8fc9)


## 8. 🌍 Geography and Time Series Dashboard

**Key Insights:**
- **Top Country**: USA ($3,627,982.83)  
- **Highest Revenue Territory**: EMEA ($4.97M)  
- **Best Performing Quarter**: Q4  
- **Peak Sales Month**: December  
- Map visuals show revenue distribution across global regions  
- Line and donut charts illustrate monthly and quarterly sales trends

# GEOGRAPHY AND TIME SERIES DASHBOARD
![Screenshot 2025-07-09 123946](https://github.com/user-attachments/assets/c9fce6ab-08fa-4ce8-905b-3b66bd2f57a9)


## 9. 🧪 Methodology

- Loaded raw dataset into Excel and cleaned using Power Query  
- Modeled data into star schema for dashboard optimization  
- Created calculated fields using DAX (e.g., month )  
- Designed multiple dashboards based on business questions  
- Used filters, slicers, and charts for interactivity and storytelling


## 10. 📈 Findings and Analysis

- A few product categories and customers contribute most of the revenue  
- Medium-sized deals generated the highest value  
- USA and EMEA territories dominate global sales  
- Clear peak in December, indicating seasonal buying patterns  
- Classic Cars and Vintage Cars are the most popular by revenue


## 11. ✔️ Recommendations

- Prioritize inventory for top-selling products (e.g., Classic Cars)  
- Focus marketing and sales efforts on the EMEA territory  
- Engage high-value customers with loyalty programs  
- Prepare for peak sales in Q4 by increasing stock and staff readiness  
- Investigate high revenue variance across countries for opportunities or inefficiencies

![WhatsApp Image 2025-07-09 at 1 18 40 PM](https://github.com/user-attachments/assets/4fb0362a-629f-4c95-8585-46e0e0b23738)

