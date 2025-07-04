# Amazon Product Review Analysis Project

## Overview

This report presents a data analysis project conducted on an Amazon product dataset using Microsoft Excel. The primary goal was to extract meaningful insights from key product metrics such as prices, ratings, reviews, and discounts, and to visualize them through a structured dashboard. The project involved data cleaning, calculated columns, pivot tables, and interactive elements like slicers to summarize trends and performance across product categories.


## Main Objectives.

Tasks focus on pricing, ratings, discount patterns, and category insights.
Understand discount patterns and their relation to product ratings.



## Methodology

- Data Source:
  Amazon product dataset with fields like title, category, rating, rating_count, actual_price, discounted_price, and discount_percentage.

- Tools Used:
  Microsoft Excel

- Techniques Applied:

- Data Cleaning: Removing blanks, formatting columns

- Calculated Columns:

  Discount Percentage

  Potential Revenue = actual_price × rating_count

  Combined Score = (rating × rating_count)
  
   ![Image](https://github.com/Omotoso-Bukola/Amazon-case-study/blob/main/My%20excel%20screenshot.png)

  
  
   ![Image](https://github.com/Omotoso-Bukola/Amazon-case-study/blob/main/Screenshot%202025-07-04%20210631.png
  )


   ![Image](https://github.com/Omotoso-Bukola/Amazon-case-study/blob/main/My%20pivot%20Table%20screenshot.png)


 - Pivot Tables: To aggregate metrics by category and rating

 - Slicers: To filter charts by category, discount range,>50% discount

 - Dashboard: Designed on a separate sheet to visualize KPIs


 ## Questions Answered

- Below are some of the key business questions explored:

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


## Dashboard Overview

- The dashboard includes:

- KPIs showing averages and totals by category

- Charts comparing actual vs discounted prices

- Top 5 products using a combined score

- Slicers to filter by category, discount range, and price range


The dashboard was built on a dedicated Excel sheet titled “Dashboard” 



## Challenges & Problems Faced

  Long Category Names: Caused chart labels to overflow or overlap

  Discount Ranges Not Grouping Correctly: Required helper column and nested IF formulas



## Conclusion

This analysis successfully uncovered critical insights from the Amazon product dataset using Excel. The combination of pivot tables, calculated fields, and a clean dashboard layout provides a strong foundation for data-driven decisions in e-commerce or product performance evaluation.
