# Eastvantage-Assignment

Assignment for Eastvantage for Data Engineering Post.

## Assignment

**Scenario**:
Company XYZ held a promo sale for their signature items named: x,y,z. Sales are at an all-time high, but they want to create a marketing strategy to target age groups of people by looking at total quantities purchased.
They then created a database with these business rules:

- A sales receipt can have multiple items in an order.
- For every order, the clerk records all quantities for all items, including items not bought (which they denote with quantity=NULL).
- Each customer can do multiple sales transactions, and has his/her age stored in a database.
**Objectives**
Create a Python script that can:

1. connect to the SQLite3 database provided.
2. extract the total quantities of each item bought per customer aged 18-35.
   - For each customer, get the sum of each item
   - Items with no purchase (total quantity=0) should be omitted from the final list
   - No decimal points allowed (The company doesn’t sell half of an item)
**Challenge**: Provide 2 solutions, one using purely **SQL**, the other using **Pandas**
3. store the query to a CSV file, delimiter should be the semicolon character (';')
