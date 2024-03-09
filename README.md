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

# Project Title

Brief description of the project.

## Introduction

Introduce the project, its objectives, and the dataset used.

## Approach Used

### Data Wrangling
- Handle missing values and ensure data quality.
- Build a database with appropriate tables and insert data.
- Create new features such as time_of_day, day_name, and month_name.

### Exploratory Data Analysis (EDA)
- Address business questions through data analysis.
- Explore insights related to cities, products, sales, and customers.

## Business Questions

### City and Branch
- How many unique cities does the data have?
- In which city is each branch located?
- Which city has the largest revenue?

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

## Future Work

Mention any future steps or improvements to the analysis or project.

## Repository Structure

Describe the structure of the repository and how to navigate through it.

## Dependencies

List any dependencies required to run the code or reproduce the analysis.

## License

Specify the license under which the project is distributed.

## Author

Provide information about the author or contributors.




