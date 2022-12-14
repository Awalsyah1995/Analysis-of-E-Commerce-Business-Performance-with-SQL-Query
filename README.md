# SQL Query Study Case: Analyzing E-commerce Business Performance


*Note: In this project, I analyzed the e-commerce business performance only with SQL Query. So, the only tool I have used is postgreSQL pgadmin14 to make SQL query.* <br>
*SQL skill requirement: filtering, logical operation, case when, group by and aggregation, subquery and joint*

As a member of the Data Analytics team, I have responsibility to analyze 3 aspects related to the company's business performance.
These aspects include customer growth, product quality and payment types.
I will process the data that has been provided to create a business performance report on these three aspects.

## 1. Data Preparation
The database is consist of 8 tables:
1. Customers
2. Geolocation
3. Order items
4. Order Payments
5. Order reviews
6. Orders
7. Product
8. Sellers.

These are the steps to prepare the dataset: <br>
1. Create a new database in pgadmin postgresql. <br>
2. Make a query to create table for each dataset.
3. Import excel file to the table for each dataset.
4. Use alter query to set primary key and foreign key for each dataset.
5. Make an ERD.

## 2. Business Performance Analysis
### A. Annual Customer Activity Growth Analysis
![mau newecust ro chart](https://user-images.githubusercontent.com/116500936/207510870-c8827aa9-7d20-488c-8806-a0284028ba5f.png)
![business performance](https://user-images.githubusercontent.com/116500936/207508812-fc4be134-e47a-43cf-8d26-26f984ae536e.png)
- There are relatively high growing of new customer and order over the year and these 2 metrics have the same line pattern in chart. This provided these 2 metrics have high correlation each other.
- The number of customer repeat order slightly decreased in 2018, therefore company needs to find the solution to increase this metric in the next year to generate more revenue. 
- The annual monthly active user increased since 2016 until 2018.

### B. Product Quality Growth
![jointable3](https://user-images.githubusercontent.com/116500936/207509111-d8d70441-db4a-4c75-a759-8ad0c22bb74d.png)
- Revenue have been growing since 2016, this is a good progress for company.
- Annual cancelled order also have been increasing, company needs to find what's the problem and the solution.
- Health and beauty product is one of the top product categori to sell but also is one of the top cancelled product category order. Company need to investigate why this phenomenon happened. 

### C. Payment Type Usage!
![payment table](https://user-images.githubusercontent.com/116500936/207509257-c82b969f-a4b4-495c-8067-267ead4816e7.png) <br>
![payment chart](https://user-images.githubusercontent.com/116500936/207509288-33650c66-b90d-453a-a2c4-02cafabb7fff.png)
- Credit card is the most used payment type, leaving a huge gap number of payment using ahead of boleto in the second place.
- Company need to make some promotion/campaign to push the use of other payment method other than credit card to widen the market share of other payment method to generate more revenue.






