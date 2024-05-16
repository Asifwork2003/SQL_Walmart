# SQL_Walmart 

## About

This project aims to explore the Walmart Sales data to understand top performing branches and products, sales trend of of different products, customer behaviour. The aims is to study how sales strategies can be improved and optimized. 

1. Product Analysis

> Conducted analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

2. Sales Analysis

> This analysis aimed to answer the question of the sales trends of product. The result of this helped to measure the effectiveness of each sales strategy that the business applies and what modifications are needed to gain more sales.

3. Customer Analysis

> This analysis uncovered the different customers segments, purchase trends and the profitability of each customer segment.

## Approach Used

1. **Data Wrangling:** This is the first step where inspection of data was done to make sure **NULL** values and missing values are detected and data replacement methods are used to replace, missing or **NULL** values.
2. **Feature Engineering:** This helped generate some new columns from existing ones.

> 1. Adding a new column named `time_of_day` to give insight of sales in the Morning, Afternoon and Evening. This helped answer the question on which part of the day most sales are made.

> 2. Adding a new column named `day_name` that contains the extracted days of the week on which the given transactions took place (Mon, Tue, Wed, Thur, Fri). This helped answer the question on which week of the day each branch is the busiest.

> 3. Adding a new column named `month_name` that contains the extracted months of the year on which the given transactions took place (Jan, Feb, Mar). this helped determine which month of the year has the most sales and profits.

3. **Exploratory Data Analysis (EDA):** Exploratory data analysis is done to answer the listed questions and aims of this project.

4. **Conclusion:**

## Business Questions To Answer

### Generic Question

1. How many unique cities does the data have?
2. In which city is each branch?

### Product

1. How many unique product lines does the data have?
2. What is the most common payment method?
3. What is the most selling product line?
4. What is the total revenue by month?
5. What month had the largest COGS?
6. What product line had the largest revenue?
5. What is the city with the largest revenue?
6. What product line had the largest VAT?
7. Which branch sold more products than average product sold?
8. What is the most common product line by gender?
9. What is the average rating of each product line?

### Sales

1. Number of sales made in each time of the day per weekday
2. Which of the customer types brings the most revenue?
3. Which city has the largest tax percent/ VAT (**Value Added Tax**)?
4. Which customer type pays the most in VAT?

### Customer

1. How many unique customer types does the data have?
2. How many unique payment methods does the data have?
3. What is the most common customer type?
4. Which customer type buys the most?
5. What is the gender of most of the customers?
6. What is the gender distribution per branch?
7. Which time of the day do customers give most ratings?
8. Which time of the day do customers give most ratings per branch?
9. Which day fo the week has the best avg ratings?
10. Which day of the week has the best average ratings per branch?

## Credits
I have completed this project with the help of a youtube tutorial: https://www.youtube.com/watch?v=Qr1Go2gP8fo
