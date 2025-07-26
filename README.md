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
Price buckets: <1000, 1000-5000, >5000
Rating buckets for distribution analysis

## Analysis and Insights

1) Average discount percentage by product category:
Using pivot table grouped by Category = 48%


3) Product count per Category:
This involved a basic count of rows by Category
See image below:
<img width="1760" height="776" alt="count-of-products-by-category" src="https://github.com/user-attachments/assets/99196155-9170-4d37-91b9-0dc0836f1110" />



4) Total Reviews per Category:
This was done by taking a sum of review by category counts and presented in a bar chart.
See image below:
<img width="1205" height="1090" alt="review-count-by-category" src="https://github.com/user-attachments/assets/d305fe30-01d9-4d51-bb22-810848ac8de6" />



5) Highest rated products by average ratings:
Top 3 products with highest rating. See table below
<img width="655" height="255" alt="products-with-highest-ratings" src="https://github.com/user-attachments/assets/19987521-a537-4eda-a2de-3cbca789bc15" />



6) Average actual price vs the discounted price by category:
Comparison of the avergae actual prices per category vs average discounted price. See line graph
<img width="1483" height="946" alt="avg-vs-disc-price-by-category" src="https://github.com/user-attachments/assets/459f983b-52c7-4aaa-81b1-2712a1eddb9a" />


7) Product with highest number of reviews:
This is sorted by review count and 96% of the products had 8 reviews.


8) Products with ≥50% Discount:
Filtering for products with ≥50% discount, and then counting the number of products that had ≥50% discount was found to be 653.


9) Rating Distribution Table:
See table below.
<img width="1211" height="760" alt="ratings-products" src="https://github.com/user-attachments/assets/6b3e1546-2d61-4de0-9312-364cecafac43" />


10) Total Potential Revenue by Category:
See chart below
<img width="1486" height="794" alt="revenue-by-category" src="https://github.com/user-attachments/assets/c4c1e244-a39b-4759-96e8-247df5c60629" />


11) Count of products in each defined price bucket:
<img width="1331" height="854" alt="price-range-by-products" src="https://github.com/user-attachments/assets/2caf595f-2fe3-4dfd-8b6d-091cdd5302ee" />


12) Discount vs Rating Correlation:
Please see image
<img width="1241" height="796" alt="discount-vs-ratings" src="https://github.com/user-attachments/assets/c11fd638-7444-4cf9-941f-09bc26b3ccf7" />


13) Products with <1,000 Reviews:
1351 products have fewer that 1000 reviews.


14) Categories with Highest Discounts:
See table below
<img width="1676" height="789" alt="over-90-discount" src="https://github.com/user-attachments/assets/d8b84aa7-3baf-4e44-a6dc-32e1ce206743" />


15) Top 5 products in terms of Rating and number of Reviews combined:
Created a weighted metric to rank top5 based on ratings and review
<img width="901" height="795" alt="weighted-score-rank" src="https://github.com/user-attachments/assets/f8b7d419-c448-4a4b-bade-d65451e6d271" />


## Key Findings and Recommendations


## Dashboard Overview

Category Summary

Product highlights, revenue projection, review heatmap
