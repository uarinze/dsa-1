Please find below my report as a Junior Data Analyst at RetailTech Insights: 

# Amazon Product Review Analysis Report
## Executive Summary

## Company Background:
RetailTech Insights: E-commerce analytics provider for sellers on Amazon.

Objective: To derive actionable insights from product and customer review data for product optimisation, marketting and engagement.

## Data Desciption:
Total Records: 1,465 products

Fields: 16 columns including product details and review metrics.

Data Source: Scrapped from Amazon product pages

Key Variables: Product name, category, price, discount, rating, review count, review titles, and content (aggregated)

## Methodology:
Tools used: Microsoft Excel (Pivot Tables, Calculated Columns)

Data cleaning:
Converted comma-separated values into structures format
Removed duplicates,
standardized price and discount values
Categorisation:
Price buckets: <200, 200-500, >500
Rating buckets for distribution analysis

## Analysis and Insights

1) Average discount percentage by product category:
Using pivot table grouped by Category = 48%

2) Product count per Category:
This involved a basic count of rows by Category
See image below:

3) Total Reviews per Category:
This was done by taking a sum of review by category counts and presented in a bar chart.
See image below:


4) Highest rated products by average ratings:
Top 3 products with highest rating. See table below

5) Average actual price vs the discounted price by category:
Comparison of the avergae actual prices per category vs average discounted price. See line graph

6) Product with highest number of reviews:
This is sorted by review count and 96% of the products had 8 reviews.

7) Products with ≥50% Discount:
Filtering for products with ≥50% discount, and then counting the number of products that had ≥50% discount was found to be 653.

8) Rating Distribution Table:
See table below.

9) Total Potential Revenue by Category:
See chart below


10) Count of products in each defined price bucket:


11) Discount vs Rating Correlation:
Please see image

12) Products with <1,000 Reviews:
1351 products have fewer that 1000 reviews.

13) Categories with Highest Discounts:
See table below

14) Top 5 products in terms of Rating and number of Reviews combined:
Created a weighted metric to rank top5 based on ratings and review

## Key Findings and Recommendations


## Dashboard Overview

Category Summary

Product highlights, revenue projection, review heatmap
