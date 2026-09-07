# DAX Measures

1. Total Sales

```DAX
Total Sales = SUM(Sales[SalesAmount])


2. Total Profit 

```DAX
Total Profit = SUM(Sales[Profit])


3.Profit Margin %

```DAX
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)


4.Total Orders 

```DAX
Total Orders = DISTINCTCOUNT(Sales[OrderID])


5.Total Customers 

```DAX
Total Customers = DISTINCTCOUNT(Sales[CustomerID])


6.Average Order Value 

```DAX
Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)


7.Total Quantity Sold 

```DAX
Total Quantity Sold = SUM(Sales[Quantity])
