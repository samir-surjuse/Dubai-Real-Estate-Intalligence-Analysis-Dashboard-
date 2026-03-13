# Dubai-Real-Estate-Intalligence-Analysis-Dashboard-
Power BI dashboard analysing Dubai housing market data to identify property pricing trends and real estate insights.

Project Overview  
This project presents an interactive real estate analysis dashboard built using Microsoft Power BI.  
The dashboard analyzes Dubai housing data to understand property price trends, property size distribution, and neighborhood-based listings.  
The goal of this project is to help investors and analysts make data-driven decisions in the real estate market.
Dataset Description
The dataset contains property information such as:
SquareFeet – Property size in square feet
Bedrooms – Number of bedrooms
Bathrooms – Number of bathrooms
Neighborhood – Location category (Urban, Suburb, Rural)
YearBuilt – Year the property was built
Price – Property selling price
Data Preparation
Data cleaning and transformation were performed using Power BI Power Query:
Removed duplicates
Handled missing values
Corrected data types
Calculated Columns
PricePerSqft = Price / SquareFeet
PropertyAge = 2025 - YearBuilt
ListingCategory = Budget / Mid-Range / High-End
Measures
Total Listings
Average Price
Average Size
Highest Price
Average Price per Sqft
Dashboard Features
KPI Cards
Total Listings
Average Property Price
Average Property Size
Average Price per Square Foot
Highest Property Price
Visualizations
Scatter Plot – Property Size vs Price
Bar Chart – Average Price by Bathrooms
Column Chart – Total Listings by Neighborhood
Pie Chart – Listings by Category
Filters
Bedrooms
Bathrooms
Neighborhood
Listing Category
Key Insights
Larger properties generally have higher prices.
Mid-range properties dominate the Dubai housing market.
Property listings are evenly distributed across neighborhoods.
Tools Used
Microsoft Power BI
Power Query
DAX
Data Visualization
Project Files
Dubai_Real_Estate_Dashboard.pbix – Power BI dashboard file
dataset.csv – dataset used for analysis
dashboard.png – dashboard preview image
Conclusion
This project demonstrates how real estate data can be transformed into actionable insights using Power BI dashboards and data visualization techniques.
