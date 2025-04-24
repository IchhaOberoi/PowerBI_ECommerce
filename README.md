# PowerBI_ECommerce

**link to the Project**:

https://drive.google.com/drive/folders/1JWSCbJZvfGDfBQGet3YKpxizzvAw95t0?usp=sharing

## Project Overview
In an e-commerce landscape where customer preferences, purchasing behavior, and efficient order fulfillment play crucial roles,the analytical prowess is vital. The challenge is to dissect these datasets to uncover patterns and insights that could revolutionize e-commerce strategies, improve customer engagement, and drive sales growth.

Harnessed the power of Power BI to transform these datasets into a compelling narrative. This involve data cleaning, effective data modeling, and strategic use of DAX for in-depth analytics.

## Data Description 

**The "EcommerceDataset1.xlsx" file contains the following columns:**

1. **OrderID**: A unique identifier for each order.
2. **CustomerName**: Name of the customer.
3. **Product**: Type of product ordered.
4. **Quantity**: Quantity of the product ordered.
5. **UnitPrice**: Price per unit of the product.
6. **OrderDate**: Date when the order was placed.
7. **ShippingCost**: Cost of shipping for the order.
8. **CustomerID**: A unique identifier for each customer.  (Primary Key)

**The "EcommerceDataset2.xlsx" file contains the following columns:**

1. **CustomerID**: A unique identifier for each customer, corresponding to the 'CustomerID' in "EcommerceDataset1.xlsx". (Foreign Key)
2. **CustomerEmail**: Email address of the customer.
3. **Country**: Country of the customer.
4. **Membership**: Membership status of the customer (e.g., Premium, VIP).
5. **SignUpDate**: Date when the customer signed up.
6. **LastOrderDate**: Date of the customer's last order.
7. **TotalSpent**: Total amount spent by the customer.
8. **Customer Communication Log:** Detailed communication logs for each customer.

## Key Analyses Performed

1. **Data Importing and Initial Exploration**
    - Import both datasets into Power BI. Perform an initial exploration. Identify any data quality issues or inconsistencies.
      
2. **Merging Datasets**
    - Merge the datasets using a suitable column as a key. Ensure that the merge is accurate and retains all necessary information.
      
3. **Cleaning: Handling Missing and irrelevant Values**
    - Identify and address missing data in both datasets. Address duplicate entries and irrelevant data points, ensuring data quality.
      
4. **Data Type Conversion**
    - Transform and normalize data where necessary for consistency across datasets.
      
5. **Creating a Calculated Column for Order Value**
    - Add a calculated column to determine the total value of each order (Quantity x UnitPrice). What is the average value of an order?
      
6. **Analyzing Customer Spending Patterns**
    - Use DAX to analyze the spending patterns of customers. Do VIP members spend more on average than Premium members?
      
7. **Segmenting Customers Based on Total Spending**
    - Create a new column to categorize customers into different spending tiers based on 'TotalSpent'. Define your own thresholds for the tiers.

8. **Product Popularity Analysis**
    - Analyze which products are the most popular in terms of quantity sold. Does this vary by country?
      
9. **Customer Loyalty Analysis**
    - Using DAX, calculate the average time between a customer's sign-up date and their last order date. What insights can you gather about customer loyalty?
      
10. **Advanced Filtering: High-Value Orders**
    - Create a report page that allows users to filter orders above a certain value. What are the characteristics of these high-value orders?
      
11. **Time Series Analysis: Order Trends**
    - Analyze how the number of orders and total sales have trended over time. Are there any noticeable seasonal trends?
      
12. **Geographical Analysis: Sales by Country**
    - Using DAX, analyze total sales by country. Which country has the highest total sales?
      
13. **Membership Impact on Order Frequency**
    - Investigate if membership status (VIP or Premium) affects the frequency of orders. Use DAX to perform this analysis.
   
14. **Calculating Average Shipping Cost**
    - Create a measure to calculate the average shipping cost per order. How does this vary by product?
      
15. **Correlation Analysis: Spending vs. Order Value**
    - Analyze if there's a correlation between 'TotalSpent' by a customer and their average order value.
      
16. **Analyzing Order Size**
    - Create a measure to analyze the average order size (quantity of products) per order. Does this vary significantly across different products?
      
17. **Customer Email Domain Analysis**
    - Extract the email domain (part after '@') from 'CustomerEmail' and analyze if the domain correlates with spending habits or membership type.
      
18. **Advanced DAX: Year-over-Year Sales Comparison**
    - Perform a year-over-year comparison of total sales. What trends or patterns do you observe?
      
19. **Extracting Key Information**
    - Using the 'Customer Communication Log' column in dataset 2, create two new columns. One column should list the dates of all communications for each customer, and the other should list the types of communications (e.g., Inquiry, Complaint, Feedback, Request).”

20. **Analyzing Customer Retention**
    - Using DAX, calculate the retention rate of customers based on their sign-up year. What does this reveal about customer loyalty?
      
21. **Customer Demographics Analysis**
    - Analyze the demographics of customers (e.g., country distribution) and correlate it with spending patterns.
      
22. **Lifetime Value (LTV) Calculation**
    - Calculate the Lifetime Value (LTV) of customers using DAX. LTV can be estimated as the average order value multiplied by the average number of orders per year, and the number of years since the customer signed up.
      
23. **Data Modeling: Cohort Analysis**
    - Perform a cohort analysis of customers based on their sign-up year. Analyze how different cohorts behave in terms of spending and order frequency.

## DashBoard Building

The project culminated in the creation of a comprehensive, interactive Power BI dashboard. The dashboard incorporated slicers, filters, and page navigation to enhance interactivity and user experience.


![image](https://github.com/user-attachments/assets/55036164-cb90-41f0-896c-be27f589f547)

      




