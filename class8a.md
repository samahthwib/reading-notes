
## **SQL**
stand for *Structured Query Language*, It's a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.

### **Relational databases**
 represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

 <SELECT>  To retrieve data from a SQL database
 <DISTINCT> By using DISTINCT SQL provides a convenient way to discard rows that have a duplicate column value 
 <ORDER BY> a way to sort your results by a given column in ascending or descending order

 EXAMPLE: 
 SELECT * FROM Customers; 

 #### Each query begins with finding the data that we need in a database, and then filtering that data down into something that can be processed and understood as quickly as possible. Because each part of the query is executed sequentially

 Query order of execution:
 1. FORM and JOIN
 2. WHERE
 3. GROUP BY
 4. HAVING
 5. SELECT
 6. DISTINCT
 7. ORDER BY
 8. LIMIT/OFFSET