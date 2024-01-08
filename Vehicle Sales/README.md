# Vehicle Sales Analysis

## Description
This project analyzes vehicle sales data to identify trends, patterns, and insights that can be used for decision-making in the automotive industry.

## Dataset
- ORDERNUMBER: A unique identification number assigned to each order.
- QUANTITYORDERED: The number of items ordered in each order.
- PRICEEACH: The price of each item in the order.
- ORDERLINENUMBER: The line number of each item within an order.
- SALES: The total sales amount for each order, calculated by multiplying the quantity ordered by the price of each item.
- ORDERDATE: The date on which the order was placed.
- DAYS_SINCE_LASTORDER: The number of days that have passed since the last order for each customer, useful for analyzing customer purchasing patterns.
- STATUS: The status of the order, such as "Shipped," "In Process," "Cancelled," "Disputed," "On Hold," or "Resolved."
- PRODUCTLINE: The product line categories to which each item belongs.
- MSRP: Manufacturer's Suggested Retail Price, representing the suggested selling price for each item.
- PRODUCTCODE: A unique code assigned to each product.
- CUSTOMERNAME: The name of the customer who placed the order.
- PHONE: The contact phone number for the customer.
- ADDRESSLINE1: The first line of the customer's address.
- CITY: The city where the customer is located.
- POSTALCODE: The postal code or ZIP code associated with the customer's address.
- COUNTRY: The country where the customer is located.
- CONTACTLASTNAME: The last name of the contact person associated with the customer.
- CONTACTFIRSTNAME: The first name of the contact person associated with the customer.
- DEALSIZE: The size of the deal or order, categorized as "Small," "Medium," or "Large."

## Key Analysis Steps
- Data cleaning and preprocessing
- Exploratory data analysis
- Visualization of sales trends
- Statistical analysis of sales performance

## Dependencies
The notebook uses the following Python libraries:

- pandas
- plotly
- matplotlib
- seaborn
