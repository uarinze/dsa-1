Please find below my 1st report for the project at IncubatorHub.

 Case Study 1: Amazon Product Review Analysis 
1. Company Overview 
You are working as a Junior Data Analyst at RetailTech Insights, a company that provides 
e-commerce analytics solutions to sellers on platforms like Amazon. Your team has been 
tasked with analysing product and customer review data to generate insights that can 
guide product improvement, marketing strategies, and customer engagement. 
2. Dataset Description 
The dataset contains information scraped from Amazon product pages, including: 
•       Product details: name, category, price, discount, and ratings 
•       Customer engagement: user reviews, titles, and content 
•       Each row represents a unique product, with aggregated reviewer data 
stored as comma-separated values 
Total 
Records: 
1,465 
TotalFields: 16 columns 
3. Analysis Tasks 
rows       
Use pivot tables and calculated columns where necessary to answer the following: 
1. What is the average discount percentage by product category? 
2. How many products are listed under each category? 
3. What is the total number of reviews per category?  
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)? 
11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined. 
4. Final Task: Dashboard Creation 
Using your cleaned dataset and pivot outputs, build an Excel dashboard. Unleash your 
Creativity 

############################################################################################################################

# Amazon Product Review Analysis Report
## Executive Summary
Amazon Product Review Analysis Prepared by: Junior Data Analyst, RetailTech Insights

**Purpose**
This analysis was conducted to extract actionable insights from Amazon product and review data. The goal is to support product optimization, enhance marketing strategies, and improve customer engagement across key e-commerce categories.

**Key Findings**
High Discounts Drive Visibility: Categories like Fashion and Beauty offer the steepest discounts (≥35%), but do not always correlate with higher ratings.
Review Volume Signals Trust: Electronics and Home & Kitchen dominate in review count and potential revenue, indicating strong customer trust and engagement.
Top Performers Identified: A select group of products—primarily in tech and skincare—excel in both ratings and review volume, making them ideal for promotional focus.
Under-Reviewed Products Are Common: Over 1,000 products have fewer than 1,000 reviews, representing a major opportunity for targeted review-generation campaigns.
Price Sensitivity Matters: Most products fall within the ₹200–₹500 range, suggesting that affordability is a key driver of customer interest.

**Strategic Recommendations**
Boost Visibility for High-Rated, Low-Review Products through targeted marketing and review incentives.
Capitalize on Top Performers by featuring them in advertising and bundling strategies.
Monitor Rating Trends Post-Discount to ensure quality perception remains intact.
Segment Marketing by Price Range to align with customer purchasing behavior.

**Dashboard Delivered**
An interactive Excel dashboard was created to visualize:
Category-level performance
Rating and review distributions
Price and discount dynamics
Top product rankings

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



5) Total Reviews per Category:
This was done by taking a sum of review by category counts and presented in a bar chart.
See image below:

<img width="1205" height="1090" alt="review-count-by-category" src="https://github.com/user-attachments/assets/d305fe30-01d9-4d51-bb22-810848ac8de6" />



6) Highest rated products by average ratings:
Top 3 products with highest rating. See table below:

<img width="655" height="255" alt="products-with-highest-ratings" src="https://github.com/user-attachments/assets/19987521-a537-4eda-a2de-3cbca789bc15" />



7) Average actual price vs the discounted price by category:
Comparison of the avergae actual prices per category vs average discounted price. See line graph:

<img width="1483" height="946" alt="avg-vs-disc-price-by-category" src="https://github.com/user-attachments/assets/459f983b-52c7-4aaa-81b1-2712a1eddb9a" />


8) Product with highest number of reviews:
This is sorted by review count and 96% of the products had 8 reviews.


9) Products with ≥50% Discount:
Filtering for products with ≥50% discount, and then counting the number of products that had ≥50% discount was found to be 653.


10) Rating Distribution Table:
See table below.

<img width="1211" height="760" alt="ratings-products" src="https://github.com/user-attachments/assets/6b3e1546-2d61-4de0-9312-364cecafac43" />


11) Total Potential Revenue by Category:
See chart below:

<img width="1486" height="794" alt="revenue-by-category" src="https://github.com/user-attachments/assets/c4c1e244-a39b-4759-96e8-247df5c60629" />


13) Count of products in each defined price bucket:
14) 
<img width="1331" height="854" alt="price-range-by-products" src="https://github.com/user-attachments/assets/2caf595f-2fe3-4dfd-8b6d-091cdd5302ee" />


15) Discount vs Rating Correlation:
Please see image:

<img width="1241" height="796" alt="discount-vs-ratings" src="https://github.com/user-attachments/assets/c11fd638-7444-4cf9-941f-09bc26b3ccf7" />


17) Products with <1,000 Reviews:
1351 products have fewer that 1000 reviews.


18) Categories with Highest Discounts:
See table below:

<img width="1676" height="789" alt="over-90-discount" src="https://github.com/user-attachments/assets/d8b84aa7-3baf-4e44-a6dc-32e1ce206743" />


20) Top 5 products in terms of Rating and number of Reviews combined:
Created a weighted metric to rank top5 based on ratings and review:

<img width="901" height="795" alt="weighted-score-rank" src="https://github.com/user-attachments/assets/f8b7d419-c448-4a4b-bade-d65451e6d271" />


## Dashboard Overview
An interactive Excel dashboard was created with the following components:
**Visuals**
Bar Charts: Average discount by category, review count per category
Pie Chart: Product distribution by category
Scatter Plot: Rating vs Discount
Table: Top 5 products by combined score

**Filters**
Category, Price Range, Rating Buckets

**KPIs**
Total Products: 1,465
Avg Rating: 4.1
Total Reviews: 11k+
Potential Revenue: ₹ 121.327Billion

## Recommendations
**Product Strategy**
Focus on high-rated, low-review products for promotional boosts.
Consider bundling products in categories with high discounts but low engagement.

**Marketing Strategy**
Leverage top-reviewed products in ad campaigns.
Target price-sensitive segments with ₹200–₹500 products.

**Customer Engagement**
Encourage reviews for under-reviewed products via incentives.
Monitor rating trends post-discount to ensure quality perception remains high.
