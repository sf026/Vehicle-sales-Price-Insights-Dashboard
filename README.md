Vehicle Sales & Price Insights Dashboard (Excel)
An interactive Excel dashboard built using Power Query and Pivot Tables to analyze vehicle selling price trends, market value (MMR)
, mileage impact, and condition-based pricing.

Project Overview
This project focuses on cleaning and transforming a real-world vehicle sales dataset and creating an industry-level dashboard to answer key business questions such as:
* Which car makes have the highest average selling price?
* How does mileage affect the selling price?
* How does vehicle condition impact pricing?
* What are the monthly trends in sales?
* Which states contribute the most sales volume?

Dataset Details
Dataset Name: Vehicle Sales and Market Trends Dataset
Format: CSV
Key Columns:

Vehicle Details: year, make, model, trim, body, transmission
Usage Metrics: condition, odometer
Pricing: mmr, sellingprice
Location & Seller: state, seller
Time: saledate

Tools & Technologies

Microsoft Excel
Power Query (Data Cleaning & Transformation)
Pivot Tables / Pivot Charts
Slicers (Interactive Filtering)

Data Cleaning & Transformation (Power Query)

Key cleaning steps performed:
Removed duplicate records using VIN
Converted saledate from Text → Date
Fixed incorrect datatypes (numeric & date columns)
Handled missing categorical values by replacing nulls with "Unknown"
Standardized categorical text (state formatting, transmission values)
Created new analytical columns for better dashboard insights

Feature Engineering (New Columns Created)

Condition Rating (normalized values like 41 → 4.1)
Condition Category: Poor / Average / Good / Excellent
Mileage Band: Low / Medium / High
Sale Month / Month Name for trend analysis

Key Insights

Make/Brand has a strong influence on selling price
Low mileage vehicles sell at higher prices than high mileage vehicles
Better vehicle condition results in better selling price
Sales and pricing vary across states and months
Automatic transmission dominates in overall sales volume

