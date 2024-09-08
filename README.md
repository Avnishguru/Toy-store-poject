# Interactive Product Sales Dashboard
## Overview
This project involves creating an interactive dashboard using Power BI to analyze product, sales, store, and calendar data. The dashboard provides insights into product performance, sales trends, store operations, and time-based analysis.
## Data Sources
### 1. Product Data:
#### Columns:
ProductKey, ProductSubcategoryKey, ProductSKU, ProductName, ModelName, ProductDescription, ProductColor, ProductSize, ProductStyle, ProductCost, ProductPrice
#### Description:
This dataset contains detailed information about each product, including its unique identifier, category, SKU, name, model, description, color, size, style, cost, and price.
### 2. Sales Data:
#### Columns:
Sale_ID, Date, Store_ID, Product_ID, Units
#### Description:
This dataset captures sales transactions, including the sale ID, date of sale, store ID, product ID, and the number of units sold.
### 3. Store Data:
#### Columns:
Store_ID, Store_Name, Store_City, Store_Location, Store_Open_Date
#### Description:
This dataset provides information about each store, including its unique identifier, name, city, location, and the date it opened.
### 4. Calendar Data:
#### Columns:
Date, Start_of_Date, Start_of_Date_Month
#### Description:
This dataset includes date-related information, with calculated columns for the start of the date and the start of the date month, facilitating time-based analysis.
## Data Model
**Entities:** Customers, Products, Sales, Date, Stores.

**Relationships:** Defined relationships between entities to enable comprehensive analysis.

**Calculated Columns:** Includes calculated columns for enhanced time-based analysis.

## Key Features
**Interactive Visualizations:** The dashboard includes various interactive charts and graphs that allow users to filter and drill down into specific data points.

**Sales Analysis:** Visualizations to track sales performance over time, identify top-selling products, and analyze sales by store location.

**Product Insights:** Detailed views of product attributes and their impact on sales, helping in inventory management and marketing strategies.

**Store Performance:** Analysis of store operations, including sales by store, store locations, and opening dates.

**Time-Based Analysis:** Insights into sales trends over different time periods, leveraging the calendar data for more granular analysis.

**User-Friendly Interface:** Designed with an intuitive layout to ensure ease of use for stakeholders.

##  Technologies Used
**Power BI:** For data visualization and dashboard creation.

## Conclusion
The interactive dashboard provides valuable insights into product, sales, store, and time-based data, enabling better decision-making and strategic planning.
