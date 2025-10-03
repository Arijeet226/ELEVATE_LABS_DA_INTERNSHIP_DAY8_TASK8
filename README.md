# ELEVATE_LABS_DA_INTERNSHIP_DAY8_TASK8
TASK 8: Simple Sales Dashboard Design, Objective: Create a basic interactive dashboard that shows sales performance by product, region, and month.

DATASET USED:-https://www.kaggle.com/datasets/jr2ngb/superstore-data

## ABOUT DATASET
Order Date – The date when the order was placed. (Some missing values: 31,223).

Ship Date – The date when the order was shipped. 1,464 unique values. No missing data.

Ship Mode – Type of shipping (e.g., Standard, Second Class, etc.). Only 4 unique categories.

Customer Name – Name of the customer. 795 unique customers.

Segment – Customer segment (e.g., Consumer, Corporate, Home Office). 3 unique categories.

City – City of the customer. 3,636 unique values.

State – State/province of the customer. 1,094 unique states.

Country – Country where the customer is located. 147 unique countries.

Market – Business market division (e.g., APAC, EU, US). 7 unique markets.

Region – Regional grouping. 13 unique regions.

Product ID – Unique identifier for products. 10,292 unique values.

Category – High-level product grouping (Furniture, Office Supplies, Technology). 3 unique categories.

Sub-Category – More specific product classification. 17 unique sub-categories.

Product Name – Name of the product. 3,788 unique products.

Sales – Revenue generated from the sale (numeric). 22,995 unique values.

Quantity – Number of items purchased. Values range across 14 distinct counts.

Discount – Discount applied to the order. 27 unique discount levels.

Profit – Profit made from the order (numeric). 24,575 unique values.

Shipping Cost – Shipping charges for the order. 10,037 unique values.

Order Priority – Priority level of the order (Critical, High, Medium, Low). 4 categories.

Project Steps:-
1. Dataset Loading(In Google Collab)
Loaded Superstore 2011-2015 dataset CSV into a pandas DataFrame

2. Data Profiling(In Google Collab)
Displayed initial rows of both datasets
Explored dataset structure and column information
Identified key columns such as orderdate, segment, shipmode, region, profit, quantity, sales, category and order priority

3. Data Cleaning(In Google Collab)
Checked for Blank Values and found out that maximum blanks are in order date column which is a key column so we can't directly
delete the whole blanks rows, we will filter it out in Power BI during visualization process. Lastly make a clean copy of the original data for further visualization and analysis.

4. Run some EDA to have a quick insight about the data.
   ### Q1. INITIAL FINDING FOR PRODUCT CATEGORY - Technology is by far has the most profit.
   ### Q2. INITIAL FINDING FOR REGION - Central region has more sale compared to any other region followed by south and then north.
   ### Q3. INITIAL FINDING FOR MONTHS - November has the highest volume of sales.
   
With this as observation, we moved to visualization part.

## VISUALIZATION USED:-(Power BI)
Donut Chart (Sales by Category)
Shows the proportional share of each product category—Technology, Furniture, Office Supplies—using a circular format for easy comparison.

Bar Chart (Sales by Region)
Vertical bars represent total sales across regions, making it straightforward to compare regional performance.

KPI Tiles/Metric Cards
Large, bold figures display sum of profit, sum of sales, and sum of quantity for rapid insights into overall performance metrics.

Line Chart (Profit and Quantity by Month)
A dual-axis chart plots sum of profit (in yellow) and sum of quantity (in blue), highlighting monthly trends over time.

Area Chart (Sales by Month)
Filled regions under the curve show monthly sales fluctuations, emphasizing changes and volume across the year.

Slicers/Filters
Region, Category, and Year selectors allow dynamic data exploration, letting users filter the entire dashboard view

## SUMMARY

Sales Distribution by Category
- The highest sales share is from Furniture (38.42%), followed by Office Supplies (31.6%), and Technology (29.98%), indicating that Furniture leads sales among the categories.

Regional Sales Leaders
- The Central region achieves the highest sales at 1.05M, which is significantly ahead of the next highest, the South region (0.62M), highlighting its dominance in revenue generation.

Monthly Sales Trend
- Sales show a notable spike in June (500K), with December reaching the year’s highest monthly sales at 613K. This suggests seasonality, possibly due to end-of-year procurement or promotions.

Profit and Quantity by Month
- Profit and quantity both trends upwards after May, peaking in August and December. August shows the highest profit (75K), and December also demonstrates strong quantity sold (9.1K), reflecting effective sales strategies or promotions during these months.

Performance Overview
- The dashboard totals indicate an overall sum of profit at 576K, sales at 5M, and quantity at 69K for the period in view, reflecting strong business performance and market penetration across regions and categories.

**Screenshot of dashboard:**  
![Preview of dashboard](https://github.com/Arijeet226/ELEVATE_LABS_DA_INTERNSHIP_DAY8_TASK8/blob/91740a09501c055cd2c45d993e13db16b5ac8457/Screenshot%202025-10-03%20131756.png)

Lately, Documented all the insights gathered from the visualization in a word file.

# --THANK YOU--
