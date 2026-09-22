# Aavin Milk Sales Analysis Using Python

## 📌 Project Overview

This project focuses on cleaning and analyzing Aavin milk sales data using Python. The analysis was performed to understand sales trends, outlet performance, product category contribution, district-wise revenue, and customer payment preferences.

The project covers data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), and data visualization using Python.

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Dataset

The dataset contains sales transaction information with the following columns:

- Order Date
- District
- Outlet Type
- Product Name
- Category
- Unit Price
- Quantity Sold
- Revenue
- Payment Mode

**Note:** The original dataset is not included in this repository.

## 🔧 Data Cleaning

The following data cleaning steps were performed:

- Checked for duplicate records and removed duplicate rows.
- Converted the order date into a proper datetime format and removed rows where the date could not be parsed.
- Checked for missing values in the dataset.
- Inspected the `unit_price` and `quantity_sold` columns for potential outliers using box plots.
- Corrected negative values in the quantity sold column by converting them to positive values.
- Filled missing unit price values using the median of the column.
- Filled missing quantity sold values using the median of the column.
- Removed rows with missing district or payment mode values.
- Standardized text columns by removing extra whitespace and applying consistent title case formatting.
- Reviewed the unique values in the text columns after standardization.
- Re-checked the dataset shape, duplicate records, missing values, and data types after cleaning to verify the results.

## 📈 Analysis Performed

### 1. Monthly Revenue Trend

Analyzed monthly revenue to understand how revenue changed over the period covered by the dataset.

**Finding:** Monthly revenue showed a fluctuating trend with several peaks and dips across the analyzed period.

### 2. Average Order Value by Outlet Type

Compared the average revenue generated per order across different outlet types.

**Finding:** Retail Shop recorded the highest average order value at approximately ₹1,650 per order.

### 3. Revenue Share by Category

Analyzed the contribution of different product categories to total revenue.

**Finding:** Ghee was the largest contributor, accounting for approximately 50.8% of total revenue.

### 4. District-wise Revenue

Compared total revenue generated across different districts.

**Finding:** Erode, Madurai, and Chennai were the top three districts by revenue. Salem, Coimbatore, and Thanjavur were the bottom three districts by revenue in this analysis.

### 5. Payment Mode Analysis

Analyzed the number of transactions made using different payment methods.

**Finding:** UPI was the most commonly used payment mode, followed closely by Cash.

## 🔍 Key Takeaways

- Monthly revenue showed fluctuations throughout the analyzed period.
- Retail Shop had the highest average order value.
- Ghee contributed the largest share of total revenue.
- Erode, Madurai, and Chennai recorded the highest district-wise revenue.
- UPI was the most commonly used payment mode.

## 📁 Project Files

- `Aavin_Milk_Sales_Analysis.ipynb` — Complete Python analysis and visualizations.
- `README.md` — Project documentation.
- `screenshots/` — Selected analysis visualizations.

## 🚀 Project Outcome

This project helped me practice data cleaning, exploratory data analysis, grouping and aggregation and data visualization using Python and Pandas.
