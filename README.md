 # 📊 SuperStore Sales Analysis

This repository contains sales data from a fictional SuperStore. The dataset includes information on orders, customers, products, sales, and profits. The goal is to analyze trends, identify insights,build useful data visualizations and improve business strategies. 

## 📁 Dataset
- **File:** `SuperStore_Sales_Dataset.csv`
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

