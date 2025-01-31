# pandas-challenge-1

This program analyzes data from a database about vendor purchases.

In order of what the parts do, the blocks are described below:

Part 1

View the column names. 

Use the describe function. 

Correctly identify the category with the most entries. 

For the category with the most entries, correctly identify the subcategory with the most entries. 

Correctly identify the 5 clients with the most entries in the data. 

Store the client ids of those top 5 clients in a list. 

Display the total units (the qty column) that the client with the most entries ordered.

Part 2

Create a column that calculates the subtotal for each line using the unit_price and the qty. 

Create a column for shipping price. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under. 

Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%. 

Create a column for the cost of each line using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client). 

Create a column for the profit of each line using line cost and line price.

Part 3

Confirm that Order ID 2742071 had a total price of $152,811.89. 

Confirm that Order ID 2173913 had a total price of $162,388.71. 

Confirm that Order ID 6128929 had a total price of $923,441.25. 

Part 4
Calculate the total revenue from each of the top 5 clients in Part 1. 

Create a summary DataFrame showing the totals for the top 5 clients with the following information: total units purchased, total shipping price, total revenue, and total profit. 

Create a function to change the currency to millions of dollars. Format the data and rename the columns to names suitable for presentation. Then, sort the DataFrame in descending order by total profits. 

Summary of your findings. 