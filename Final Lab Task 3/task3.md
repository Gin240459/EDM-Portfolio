# Final Task 3: Table Manipulation
## Task Description
Created and modified a MySQL table called "products" with appropriate data types and constraints, including a CHECK constraint for positive pricing. Inserted valid data and adjusted field lengths using ALTER statements.

# Step 1
Create a table name products with the following field:
- id: Unique integer, auto_increment, primary key.
- product_name: String (VARCHAR) with a maximum length of 100, cannot be null
- price: Decimal.


# Task 2: 
- Add CHECK constraint to ensure that the price of the product must be greater than 0.


 # Step 3
Insert the products that will not violate the check constraint into the products table:
- Product 1: "Laptop", 999.99
- Product 2: "Headphones", -49.99
- Product 3: "Smartphone", 599.99
- Product 4: "Tablet", 299.99
- Product 5: "Monitor", -149.99
- Product 6: "Keyboard", 19.99
- Product 7: "Mouse", 14.99
- Product 8: "Desk Lamp", 24.99
- Product 9: "External Hard Drive", -79.99
- Product 10: "Speakers", 9.99
<img src="INSERTproduct.png" alt="Alt Text" width="500" height="300">

# Task 4:

#  Query Statement
<img src="InsertProductTBL.png" alt="Alt Text" width="500" height="300">

# Product Table


## ER Diagram Representation


## SQL Copy of the Database
**Download the complete SQL file here:** [Table Manipulation]
