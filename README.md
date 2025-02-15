![Screenshot 2025-02-15 162826](https://github.com/user-attachments/assets/852b9da6-e899-4c66-9ea8-0ba32865fd09) # 📊 SuperStore Sales Analysis

This repository contains sales data from a fictional SuperStore. The dataset includes information on orders, customers, products, sales, and profits. The goal is to analyze trends, identify insights,build useful data visualizations and improve business strategies. 

## 📁 Dataset
- **File:** `SuperStore_Sales_Dataset.csv`
- **Tool Used:** Microsoft Power BI
- **Columns:** Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Profit, Returns, Payment Mode, ind1, ind2


## 🧼 Data Cleaning Steps

To ensure data quality, the following cleaning steps were applied to the **SuperStore Sales Dataset**:

1️⃣ **Remove Unnecessary Columns**  
   - Dropped irrelevant columns like `Row ID`, `ind1`, and `ind2`.  

2️⃣ **Handle Missing Values**  
   - Removed rows with missing values in key columns (`Order ID`, `Customer ID`, `Product ID`).  
   - Filled missing values in `Profit`, `Sales`, or `Quantity` with appropriate defaults (0 or median).  

3️⃣ **Remove Duplicates**  
   - Checked for duplicate rows based on `Order ID` and `Product ID` and removed them.  

4️⃣ **Standardize Date Formats**  
   - Converted `Order Date` and `Ship Date` to `YYYY-MM-DD` format.  

5️⃣ **Fix Data Types**  
   - Converted `Sales`, `Profit`, and `Quantity` to numeric format.  
   - Ensured `Order Date` and `Ship Date` were in datetime format.  

6️⃣ **Remove Outliers**  
   - Detected and removed extreme values in `Sales`, `Profit`, and `Quantity` using statistical methods (e.g., Z-score or IQR).  

7️⃣ **Standardize Text Fields**  
   - Converted text columns (`Customer Name`, `Product Name`, `Category`) to title case.  
   - Removed extra spaces and special characters.  

The cleaned dataset is saved as **SuperStore_Sales_Cleaned.csv** and is ready for analysis. 🚀


![Screenshot 2025-02-15 162803](https://github.com/user-attachments/assets/b03a3196-8476-4212-b294-12816ad51d9c)

📊This repository contains a Power BI dashboard that visualizes Super Store Sales Data, providing insights into sales, profit, and product performance across different categories, segments, and regions.

🔥 Dashboard Overview

1️⃣ Sales by Payment Mode
This donut chart represents the distribution of sales by payment mode:
 
2️⃣ Sales by Segment
This visualization breaks down sales by customer segments:
 
3️⃣ Sales by Ship Mode
Sales distribution based on shipping methods

 📌 Sales by Category
 ![Category Sales](https://github.com/user-attachments/assets/04cc096d-54bd-43be-8e90-de4890c1d7df)


4️⃣ Sales & Profit Trends
Sum of Sales by Month and Year: Line chart showing monthly sales trends for different years.
Sum of Profit by Month and Year: Line chart displaying profit variations over months.

![Sales   Profit Trends](https://github.com/user-attachments/assets/80a2b057-0ba3-4bed-82fa-d798f3f4ef27)

📌 Category-wise Sales Breakdown
Sales by SubCategory
This bar chart displays sales performance by product subcategories:

Sales by Category
This visualization shows sales totals by broader product categories:



 

