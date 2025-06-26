# Task-3-Basic-SELECT-Queries
Demonstrates basic SQL queries using SELECT statements.

# Queries Included:
- Selecting all rows and specific columns
  select * from product;
  select name, price from product;
  
- Filtering with WHERE, AND, OR
  select * from product where category = 'Electronics';
  select * from product where category = 'Electronics' and price < 40000;
  
- Pattern matching with LIKE
  select * from product where name like '%note%';
  
- Range filters with BETWEEN
  select * from product where price between 1000 and 20000;
  
- Sorting using ORDER BY
  select * from product order by price desc;
  
- Limiting results using LIMIT
 select * from product order by price desc limit 3;

# Output:
A series of SELECT queries to retrieve and filter data from the `products` table.

