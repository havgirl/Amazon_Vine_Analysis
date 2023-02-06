# Amazon_Vine_Analysis

## Objective
The goal of this challenge is to assess Amazon product reviews. Using AWS RDS instance, PySpark and PgAdmin we will analyze the product data and reviews, additionally assessing if being a Vine member influences customer reviews.  To achieve this we will complete the following deliverables:
- Perform ETL on Amazon Product Reviews
- Determine Bias of Vine Reviews

### Deliverable 1: Performing an ETL on Amazon Product Reviews
To complete this activity we will be achieving the following tasks:
- Create an AWS RDS database with tables in pgAdmin
- Pick a dataset from Amazon Reviews: **JEWELRY**
- Extract the dataset into a DataFrame
- Transform the DataFrame inot four separate DataFrames/Tables and publish the results

### Deliverable 1: Results

**CUSTOMER DATA TABLE**

*Data: customer_id, customer_count*

![](Images/screenshot_customers_table.png)

**PRODUCTS DATA TABLE *

*Data: product_id, product_title*

![](Images/screenshot_products_table.png)

**REVIEW ID DATA TABLE**

*Data: review_id, customer_id, product_id, product_parent, review_date*

![](Images/screenshot_review_id_table - CSV.png)

**VINE DATA TABLE**

*Data: review_id, star_rating, helpful_votes, total_votes, vine, verified_purchase*

![](Images/screenshot_vine_table.png)



