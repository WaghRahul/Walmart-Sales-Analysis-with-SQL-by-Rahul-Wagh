# Walmart-Sales-Analysis-with-SQL-by-Rahul-Wagh

## Aim
The project aims to analyze and derive insights from Walmart's sales data to improve business decision-making processes.

## Dataset Description
**The dataset consists of the following columns:**
- `Invoice_ID`: Unique identifier for each invoice.
- `Branch`: Branch of the store where the sale took place.
- `City`: The city where the store branch is located.
- `Customer_type`: Type of customer (e.g., Member, Normal).
- `Gender`: Gender of the customer.
- `Product_line`: Category of the product sold.
- `Unit_price`: Price per unit of the product.
- `Quantity`: Quantity of the product sold.
- `Tax_5%`: Tax applied on the sale.
- `Total`: Total amount of the sale.
- `Date`: Date of the transaction.
- `Time`: Time of the transaction.
- `Payment`: Payment method used (e.g., Cash, Credit Card).
- `cogs`: Cost of goods sold.
- `gross_margin_percentage`: Gross margin percentage.
- `gross_income`: Gross income from the sale.
- `Rating`: Customer rating for the purchase.

## Technique Utilized
1. **Data Preparation:**
  - Import Necessary Libraries
  - Load CSV file from DataFrame
  - Establish a Connection with SQL Database
  - Update the `Date` column to match the desired format 

2. **Feature Engineering:**
  - Add a new column to store the `time of the day`
  - Add a new column to store the `day name`
  - Add a new column to store the `month name`

3. **Exploratory Data Analysis (EDA):** Exploratory data analysis is done to answer the listed questions.
5. **Conclusion:**

## Questions to Answer
1. Retrieve all columns for sales made in a specific branch (e.g., Branch 'A').
2. Find the total sales for each product line.
3. List all sales transactions where the payment method was 'Cash'.
4. Calculate the total gross income generated in each city. 
5. Find the average rating given by customers in each branch. 
6. Determine the total quantity of each product line sold.
7. List the top 5 products by unit price. 
8. Find sales transactions with a gross margin percentage greater than 30%.
9. Retrieve sales transactions that occurred on weekends.
10. Calculate the total sales and gross income for each month. 
11. Find the number of sales transactions that occurred after 6 PM.
12. List the sales transactions that have a higher total than the average total of all transactions. 
13. Calculate the cumulative gross income for each branch by date. 15. Find the total cogs for each customer type in each city
