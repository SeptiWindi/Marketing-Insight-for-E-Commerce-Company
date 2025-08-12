**Project Overview**

This project explores a comprehensive marketing and sales dataset from a leading E-Commerce company to derive actionable insights and recommendations. The goal is to analyze customer behavior, sales trends, and marketing performance, and to build predictive models for customer segmentation and lifetime value. The analysis addresses questions such as revenue generation, customer acquisition/retention, discount and marketing effectiveness

**The explorations are :**

-  Calculate transactional revenue (invoice amount) including discounts, taxes, and delivery charges.
-  Conduct detailed exploratory analysis of sales and customer data to identify patterns (e.g., seasonality, regional trends, product demand)
-  Perform customer segmentation (RFM analysis and K-Means) to profile customers into strategic groups
-  Develop predictive models: churn prediction (classification) and customer lifetime value estimation (regression).
-  Perform cohort analysis and evaluate marketing ROI, coupon and tax effects, and product performance.
-  Ultimately, the insights will inform marketing strategies, such as targeting high-value segments and optimizing spend across channels, to maximize ROI and customer lifetime value.

**Data Loading & Basic Exploration**

By loading the provided CSV files into pandas DataFrames and performing initial exploratory analysis. The dataset comprises five files:

1. Online_Sales.csv: transactional sales data (order IDs, product details, customer IDs, quantities, unit price, delivery charges, coupon usage, etc.).
2. Customers_Data.csv: customer demographics (CustomerID, gender, location, tenure, etc.).
3. Discount_Coupon.csv: discount percentages by product category and month.
4. Marketing_Spend.csv: daily marketing expenditure on online and offline channels.
5. Tax_Amount.csv: GST tax percentage for each product category.
