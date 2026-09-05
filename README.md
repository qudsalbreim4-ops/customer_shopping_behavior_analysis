Customer Shopping Behavior Analysis
Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases.

The main purpose of the project is to understand customer spending patterns, product preferences, subscription behavior, discount usage, shipping preferences, and customer loyalty.

The project follows a complete data analysis workflow using Python, PostgreSQL, SQL, and Power BI.

Dataset

The dataset contains 3,900 records and 18 columns.

The main features include:

Customer demographics such as age, gender, location, and subscription status
Purchase information such as item, category, purchase amount, season, size, and color
Shopping behavior such as discounts, previous purchases, purchase frequency, payment method, review rating, and shipping type

There were 37 missing values in the Review Rating column.

Data Preparation

Python and pandas were used to prepare and clean the dataset.

The main steps included:

Loading and exploring the dataset
Checking the dataset structure and descriptive statistics
Handling missing values in Review Rating
Standardizing column names using snake_case
Creating an age_group feature
Creating a purchase_frequency_days feature
Checking the consistency between discount_applied and promo_code_used
Removing the redundant promo_code_used column
Loading the cleaned dataset into PostgreSQL
SQL Analysis

PostgreSQL was used to perform business-oriented analysis.

The main questions analyzed were:

Revenue by gender
High-spending customers who used discounts
Top five products by average rating
Comparison between Standard and Express shipping
Subscribers versus non-subscribers
Products with the highest percentage of discounted purchases
Customer segmentation into New, Returning, and Loyal customers
Top three products within each category
Relationship between repeat buyers and subscriptions
Revenue by age group
Customer Segmentation

Customers were divided into three segments based on their previous purchases:

New: Up to 5 previous purchases
Returning: 6 to 10 previous purchases
Loyal: More than 10 previous purchases

This segmentation helps identify different customer groups and supports targeted marketing strategies.

Power BI Dashboard

Power BI was used to create an interactive dashboard for presenting the main findings visually.

The dashboard helps analyze customer behavior, revenue, products, subscriptions, discounts, and other important business factors.

Key Findings

Some of the main findings from the analysis include:

Male customers generated higher total revenue because they represent a larger number of purchase records.
Express shipping had a higher average purchase amount than Standard shipping.
Loyal customers represent an important customer segment and contribute a large portion of revenue.
Revenue contribution differs between age groups.
Some products have higher average review ratings and can be considered for promotional campaigns.
The percentage of discounted purchases varies between products.
Repeat buyers did not show a significantly higher subscription rate compared with the overall customer base.
Business Recommendations

Based on the analysis, several recommendations can be made:

Increase the attractiveness of subscription programs through exclusive benefits and rewards.
Develop loyalty programs for repeat customers.
Review discount strategies based on individual product behavior.
Promote highly rated and popular products.
Focus marketing campaigns on high-revenue customer groups.
Evaluate Express shipping as a premium service.
Tools and Technologies
Python
Pandas
PostgreSQL
SQL
Power BI
Jupyter Notebook
Project Structure
Customer_Shopping_Behavior_Analysis/
│
├── customer_shopping_behavior.csv
├── customer_shopping_behavior_analysis.ipynb
├── customer_shopping_behavior.sql
├── customer_shopping_behavior_dashboard.pbix
├── customer_shopping_behavior_report.docx
├── customer_shopping_behavior_report.pdf
└── README.md
Conclusion

This project demonstrates a complete data analysis workflow starting from raw customer shopping data and continuing through data cleaning, feature engineering, database integration, SQL analysis, and Power BI visualization.

The project provides insights into customer spending, product preferences, discounts, subscriptions, shipping, customer loyalty, and age groups. These insights can help support better marketing, customer retention, product promotion, and business decision-making.
