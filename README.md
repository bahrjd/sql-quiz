# SQL QUIZ

- What data would be contained in the left join of two tables?

- What data would be contained in the right join of two tables?

- What data would be contained in the inner join of two tables?

- What data would be contained in a full join of two tables?

- What tool can be used to track all the queries being used by an application?

- What tool can be used to analyze a query?

- Describe CRUD.

- What does it mean if a database is ACID compliant?

- What global variable contains the identity value of the last record inserted into a database?

- What function can be used to get the current date and time?

- TRUE or FALSE: when a table has a primary key, the value of that column is automatically incremented every time a new record is inserted into that table.

- What is a primary key and why do we use them.

- What is a foreign key and why do we use them.

- What is one way to improve the search performance of a table?

- If you are going to perform a series of transactions and you wish to undo the transactions if one fails, what functionality could you use to undo the changes?

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

- Write a query to view all customers alphabetically by last name.

- Write a query to insert a new customer into the customer table.

- Write a query to update Harry Potter's email to harry.potter@aol.com

- Write a query to inner join the customer table with the order table.

- Write a query to show which customers have not placed an order.

- Write a query to show the number of orders for each customer.
