# Walmart-Sales-Analysis
This project aims to explore the Walmart Sales data to understand top performing branches and products, sales trend of different products, and customer behavior. The aim is to study how sales strategies can be improved and optimized.

## Purposes Of The Project
The major aim of this project is to gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches.

## About Data
This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows:
### Data Columns

| Column                    | Description                            | Data Type      |
|---------------------------|----------------------------------------|----------------|
| invoice_id                | Invoice of the sales made              | VARCHAR(30)    |
| branch                    | Branch at which sales were made        | VARCHAR(5)     |
| city                      | The location of the branch             | VARCHAR(30)    |
| customer_type             | The type of the customer               | VARCHAR(30)    |
| gender                    | Gender of the customer making purchase | VARCHAR(10)    |
| product_line              | Product line of the product sold       | VARCHAR(100)   |
| unit_price                | The price of each product              | DECIMAL(10, 2) |
| quantity                  | The amount of the product sold         | INT            |
| VAT                       | The amount of tax on the purchase      | FLOAT(6, 4)    |
| total                     | The total cost of the purchase         | DECIMAL(10, 2) |
| date                      | The date on which the purchase was made| DATE           |
| time                      | The time at which the purchase was made| TIMESTAMP      |
| payment_method            | The total amount paid                  | DECIMAL(10, 2) |
| cogs                      | Cost Of Goods sold                     | DECIMAL(10, 2) |
| gross_margin_percentage   | Gross margin percentage                | FLOAT(11, 9)   |
| gross_income              | Gross Income                           | DECIMAL(10, 2) |
| rating                    | Rating                                 | FLOAT(2, 1)    |

## Analysis List
### Product Analysis
- Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

### Sales Analysis
- This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.

### Customer Analysis
- This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.

## Approach Used

### Data Wrangling
### Feature Engineering
### Exploratory Data Analysis (EDA)

## Business Questions

### Generic Question
- 1 How many unique cities does the data have?
- 2 In which city is each branch?
### Product
- How many unique product lines does the data have?
- What is the most common payment method?
- What is the most selling product line?
- What is the total revenue by month?

### Sales
- Number of sales made in each time of the day per weekday.
- Which customer type brings the most revenue?
- Which city has the largest tax percent/ VAT?
- Which customer type pays the most in VAT?

### Customer
- How many unique customer types does the data have?
- What is the most common customer type?
- What is the gender distribution per branch?
- Which time of the day do customers give most ratings?

## Conclusion

Summarize key findings and insights from the analysis.





