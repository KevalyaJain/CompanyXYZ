# CompanyXYZ
## Business problem
Company XYZ held a promo sale for their signature items named: x,y,z. Sales are at an 
all-time high, but they want to create a marketing strategy to target age groups of people by 
looking at total quantities purchased.
### Business rules:
* A sales receipt can have multiple items in an order. 
* For every order, the clerk records all quantities for all items, including items not 
bought (which they denote with quantity=NULL). 
* Each customer can do multiple sales transactions, and has his/her age stored in a 
database.
## Data
As data was not provided therefore i manually inserted the data in created DataBase with 4 Tables
* Sales
* Customer
* Orders
* Items
## Steps
* Connected to the SQLite3 database provided
* Extracted the total quantities of each item bought per customer aged 18-35. 
- For each customer, got the sum of each item 
- Items with no purchase (total quantity=0) was omitted from the final 
list 
- Removed all decimal points (The company doesn’t sell half of an item ;) 
## Approach
* Using purely SQL
* The other using Pandas 
## Output 
 Stored the query to a CSV file, delimiter should be the semicolon character (';') 
