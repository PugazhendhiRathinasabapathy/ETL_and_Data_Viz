# 📊 ETL Process Implementation and Sales Dashboard using Tableau, Snowflake, and Airbyte  

## 🚀 Overview  
This project involves an **ETL pipeline** using **Snowflake** for cloud data warehousing, **Airbyte** for data integration, and **Tableau** for data visualization. It aims to process, clean, and visualize sales data to provide meaningful insights into customer purchasing behavior, pricing trends, and product performance.

We designed the ETL process, implemented it using Snowflake and Airbyte, and created a **Sales Analytics Dashboard** in Tableau. This project emphasizes the full data lifecycle, from data extraction and integration to visualization and reporting.

## 📈 Key Features  
- **Top Customers**: Identifies customers with the highest purchases.  
- **Sales Trends**: Analyzes order amounts over time.  
- **Price Analysis**: Compares **MSRP vs. Actual Price**.  
- **Best-Selling Products & Brands**: Highlights top-performing products.  
- **State-wise Sales Distribution**: Visualizes regional sales trends.  
- **Interactive Filters**: Users can dynamically filter data by brand, price, and sales count.

## 🔧 Tools Used  
- **Tableau** – Data visualization and dashboarding  
- **Snowflake** – Cloud data warehousing and data storage  
- **Airbyte** – Data integration, extraction, and loading  
- **Excel/CSV** – Data source for sales data  
- **Data Cleaning & Preprocessing** – Performed using Tableau and Airbyte  

## 🎯 Key Learnings and Insights  
1. **Strong Planning is Key**: The process highlighted the importance of planning the data pipeline, including understanding data sources, defining transformation rules, and aligning with business objectives.  
2. **Technology Decisions**:  
   - **Snowflake** enabled scalable, fast storage and analysis of large data volumes.  
   - **Airbyte** provided an easy-to-use platform for seamless data extraction and loading.  
   - **Tableau's** interactive features helped create meaningful and convincing visualizations.  
3. **Challenges Encountered**:  
   - Data quality issues and schema changes were encountered and had to be handled efficiently.  
   - Performance optimizations were necessary to handle large data volumes, especially during data transformation and loading processes.  
4. **Continuous Monitoring**: Maintaining up-to-date data required continuous monitoring of data pipelines to ensure timely and accurate reporting.

## 📷 Dashboard Preview  

<img width="960" alt="Screenshot 2025-04-02 at 7 48 26 PM" src="https://github.com/user-attachments/assets/ff9ff4d9-3d4c-4c4a-ad42-dbd5b7432e82" />

## 📂 Repository Structure  
```bash
/Sales-Dashboard  
│── /data (Contains sample dataset)  
│── /images (Dashboard screenshots)  
│── sales_dashboard.twb (Tableau workbook file)  
│── README.md (Project documentation)  
│── /scripts (ETL process scripts using Snowflake and Airbyte)  
