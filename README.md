# About the Dataset
We have 3 structured relations called **Customers**,**Products**,**Transactions**.
In the the Customers table we have the basic details for the customers like
CustomerID,Customer Name,Region,Signup Date then we have the 
Product table where we have ProductID,Product Name,Category,Price for every product and finally we have the 
Transactions table(Master Table) where we have TransactionID,CustomerID,ProductID,Transaction Date,Quantity,Total Value,Price.

## Explaining Columns:
1. **Customers.csv** [Link](https://drive.google.com/file/d/1hG0FoFjoTjyiRWSoGCauFsTFOXVghtqA/view?usp=sharing):

       ○ CustomerID: Unique identifier for each customer.
       ○ CustomerName: Name of the customer.
       ○ Region: Continent where the customer resides.
       ○ SignupDate: Date when the customer signed up.
2. **Products.csv**[Link](https://drive.google.com/file/d/1ud90txvMDhXGRBysyITP8JKD33bkNQBz/view?usp=sharing):


       ○ ProductID: Unique identifier for each product.
       ○ ProductName: Name of the product.
       ○ Category: Product category.
       ○ Price: Product price in USD.
3. **Transactions.csv**[Link](https://drive.google.com/file/d/1APPb4FntbrTa3fMlqjLMLc5PWKJe3rOs/view?usp=sharing):


       ○ TransactionID: Unique identifier for each transaction.
       ○ CustomerID: ID of the customer who made the transaction.
       ○ ProductID: ID of the product sold.
       ○ TransactionDate: Date of the transaction.
       ○ Quantity: Quantity of the product purchased.
       ○ TotalValue: Total value of the transaction.
       ○ Price: Price of the product sold.


## Clustering:

![image](https://github.com/user-attachments/assets/96f13a43-67f7-4a6c-99f8-495a866d4fbe)


                 ○ Merged the Customers and Transactions datasets to create a unified view of customer behavior.

                 ○ Conducted thorough null value checks and handled missing data appropriately.

                 ○ Extracted additional time-based features (Day, Month, Year, Hour, Minute, Second) from the TransactionDate column to enrich the dataset.

                 ○ Applied MinMaxScaler to normalize feature values and ensure that features with larger ranges did not dominate the clustering algorithm.

                 ○ Implemented K-Means clustering to segment customers based on transactional behavior.

                 ○ Evaluated clustering performance using:

                 ○ Elbow Method to determine the optimal number of clusters.

                 ○ Silhouette Score and Davies-Bouldin Score to assess clustering quality.

                 ○ Based on the evaluation, finalized the model with 4 distinct clusters.
