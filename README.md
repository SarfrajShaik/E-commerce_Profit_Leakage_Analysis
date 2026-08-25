E-Commerce Profit Leakage Analysis Project

* Project Overview -
  This project analyses an e-commerce Superstore dataset to identify where profitability is leaking and the key business factors contributing to losses.
  Using Python for data cleaning and exploratory analysis and Power BI for dashboard development, the project investigates profitability across products, sub-
  categories, regions, customer segments, discount levels and time.
  The objective was not only to identify loss-making areas but also to uncover the potential drivers behind those losses and provide actionable business
  recommendations.

* Business Problem - 
  Despite generating strong overall sales, an e-commerce business can experience significant profitability issues when certain products, regions or discount
  strategies consistently generate losses.
  This project aims to answer questions such as:
  - Which products and sub-categories are causing the largest losses?
  - How does discounting affect profitability?
  - Which regions have weaker profit margins?
  - Which customer segments are the most profitable?
  - How has sales and profit performance changed over time?
  - Where should management focus to reduce profit leakage?

* Tools & Technologies - 
  - Python
  - Pandas
  - Jupyter Notebook
  - Power BI
  - GitHub

* Dataset - 
  The dataset contains 9,994 cleaned records of e-commerce transactions from 2014 to 2017.
  Key Features:
  - Order Date
  - Ship Date
  - Ship Mode
  - Customer Segment
  - Region
  - Category
  - Sub-Category
  - Product Name
  - Sales
  - Quantity
  - Discount
  - Profit
  > Additional analytical columns were created during the project:
  - Profit Margin
  - Year
  - Loss Amount

* Data Preparation -
  The dataset was prepared using Python and Pandas.
  Key steps included:
  - Inspecting data types
  - Checking missing values
  - Validating the dataset structure
  - Converting date columns into datetime format
  - Creating a Year column for time-based analysis
  - Creating a Profit Margin metric
  - Creating a Loss Amount metric
  - Performing exploratory data analysis

* Key KPIs - 
  (KPI| Value)
  Total Sales| $2.30M
  Total Profit| $286.40K
  Overall Profit Margin| 12.47%
  Total Loss Amount| $156.13K
  Loss-Making Orders| 18.72%

* Dashboard -
  "E-Commerce Profit Leakage Analysis Dashboard" (images/dashboard.png)

  The Power BI dashboard includes:
  - Total Sales
  - Total Profit
  - Overall Profit Margin
  - Loss-Making Percentage
  - Total Loss Amount
  - Sales and Profit Trend
  - Profit by Region
  - Profit by Sub-Category
  - Discount vs Profit Analysis
  - Top 10 Loss-Making Products
  - Interactive slicers for Year, Region, Category and Segment

* Key Insights - 
  1. Profit leakage is concentrated in a few areas
  Tables generated the largest sub-category loss, followed by Bookcases and Supplies.
  This indicates that overall profitability is being affected disproportionately by specific product groups rather than all areas of the business.

  2. High discounts are strongly associated with lower profitability
  The analysis showed that profit margins were generally positive at lower discount levels but became increasingly negative as discounts increased.
  Discount levels above approximately 30% were frequently associated with negative profitability.

  3. Central region has the weakest profit margin
  The Central region generated substantial sales but had the lowest overall profit margin among all regions.
  This suggests that pricing, discounting or product mix may require further investigation in this region.

  4. Sales increased significantly over time
  Sales increased from approximately $484K in 2014 to $733K in 2017.
  Profit also increased during this period, although profit margin performance did not improve at the same rate.

  5. A small group of products generates disproportionate losses
  The analysis identified several individual products with significant negative profitability.
  These products should be prioritised for review of:
  - Pricing
  - Discounting
  - Cost structure
  - Product strategy

* Business Recommendations - 
  Based on the analysis:

  - Review discount strategies, particularly for discounts above 30%.
  - Investigate pricing and profitability of Tables and other loss-making sub-categories.
  - Prioritise the highest loss-making products for immediate review.
  - Analyse the Central region to identify the causes of its relatively weak profit margin.
  - Introduce product-level profitability monitoring before approving large discounts.

* Project Structure -
  Ecommerce-Profit-Leakage-Analysis\
  -> data/superstore_cleaned.csv
  -> dashboard/Ecommerce_Profit_Leakage_Analysis.pbix
  -> images/dashboard.png
  -> README.md

* Project Outcome - 
  This project demonstrates an end-to-end data analytics workflow:

Raw Data → Data Cleaning → Exploratory Analysis → Business Insights → Interactive Power BI Dashboard → Business Recommendations
The project focuses on translating raw transactional data into actionable insights that can support profitability and decision-making.

Author:
Sarfraj Shaik
