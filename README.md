# About the Dataset
We have 3 structured relations called **Customers**,**Products**,**Transactions**.
In the the Customers table we have the basic details for the customers like
CustomerID,Customer Name,Region,Signup Date then we have the 
Product table where we have ProductID,Product Name,Category,Price for every product and finally we have the 
Transactions table(Master Table) where we have TransactionID,CustomerID,ProductID,Transaction Date,Quantity,Total Value,Price.

## Explaining Columns:
1. **Customers.csv**:

       ○ CustomerID: Unique identifier for each customer.
       ○ CustomerName: Name of the customer.
       ○ Region: Continent where the customer resides.
       ○ SignupDate: Date when the customer signed up.
2. **Products.csv**:


       ○ ProductID: Unique identifier for each product.
       ○ ProductName: Name of the product.
       ○ Category: Product category.
       ○ Price: Product price in USD.
3. **Transactions.csv**:


       ○ TransactionID: Unique identifier for each transaction.
       ○ CustomerID: ID of the customer who made the transaction.
       ○ ProductID: ID of the product sold.
       ○ TransactionDate: Date of the transaction.
       ○ Quantity: Quantity of the product purchased.
       ○ TotalValue: Total value of the transaction.
       ○ Price: Price of the product sold.
