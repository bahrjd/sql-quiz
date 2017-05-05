# SQL QUIZ

- What data would be contained in the left join of two tables?

LEFT JOIN would include matching records from the right table and all records from the left regardless of match

- What data would be contained in the right join of two tables?

RIGHT JOIN would include matching records from the left table and all records from the right regardless of match

- What data would be contained in the inner join of two tables?

INNER JOIN would contain only data that has matches within both tables

- What data would be contained in a full join of two tables?

FULL JOIN would show all records from both tables regardless of matches

- What tool can be used to track all the queries being used by an application?

SQL Server Profiler

- What tool can be used to analyze a query?

Display Estimated Execution Plan

- Describe CRUD.

CRUD is operations Create, Retrieve, Update, and Delete objects or records. In SQL these would correspond as follows:
Create = Insert
Retrieve = Select
Update = Update
Delete = Delete

- What does it mean if a database is ACID compliant?

???

- What global variable contains the identity value of the last record inserted into a database?

@@IDENTITY

- What function can be used t

getdate()

- TRUE or FALSE: when a table has a primary key, the value of that column is automatically incremented every time a new record is inserted into that table.

FALSE

- What is a primary key and why do we use them.

A Primary Key is a unique value used to reference individual records in a table

- What is a foreign key and why do we use them.

A Foreign Key is a field that has a relationship with the Primary Key of another table. Foreign keys are used to maintain data integrity by ensuring that any data dependencies exist prior to creating a new record that is dependent on the data linked by the foreign key.

- What is one way to improve the search performance of a table?

Creating a Search Index

- If you are going to perform a series of transactions and you wish to undo the transactions if one fails, what functionality could you use to undo the changes?

Revert a TRANS

Use the following tables for the next questions:

### Customer Table:

| CustomerId | FirstName | LastName | Email                        |
|------------|-----------|----------|------------------------------|
| 101        | Harry     | Potter   | harry.potter@gmail.com       |
| 102        | Ron       | Weasley  | ron.weasley@yahoo.com        |
| 103        | Hermione  | Granger  | hermione.granger@hotmail.com |
| 104        | Draco     | Malfoy   | draco.malfoy@juno.com        |

### Order Table:

| OrderId | CustomerId | OrderDate  |
|---------|------------|------------|
| 101     | 101        | 2017-01-01 |
| 102     | 102        | 2017-01-02 |
| 103     | 103        | 2017-01-03 |
| 104     | 103        | 2017-01-04 |

- Write a query to view all customers.

SELECT * FROM dbo.Customer

- Write a query to view all customers alphabetically by last name.

SELECT * FROM dbo.Customer
ORDER BY LastName;

- Write a query to insert a new customer into the customer table.



- Write a query to update Harry Potter's email to harry.potter@aol.com

- Write a query to inner join the customer table with the order table.

- Write a query to show which customers have not placed an order.

- Write a query to show the number of orders for each customer.
