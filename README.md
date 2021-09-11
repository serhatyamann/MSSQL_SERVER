# MS_SQL_SERVER
### Microsoft SQL Server is a relational database management system developed by Microsoft. As a database server, it is a software product with the primary function of storing and retrieving data as requested by other software applications—which may run either on the same computer or on another computer across a network (including the Internet).

> My samples are coded for "BikeStores" sample database. You can find its creation scripts at https://www.sqlservertutorial.net/sql-server-sample-database/

### [Stored Procedures](https://github.com/serhatyamann/MS_SQL_SERVER/tree/main/STORED_PROCEDURES)

#### SQL Server stored procedure is a batch of statements grouped as a logical unit and stored in the database. The stored procedure accepts the parameters and executes the T-SQL statements in the procedure, returns the result set if any. Stored procedures can be reused over and over again. So if you have an SQL query that you write over and over again, save it as a stored procedure, and then just call it to execute it.

### [Functions](https://github.com/serhatyamann/MS_SQL_SERVER/tree/main/FUNCTIONS)

#### SQL server functions are sets of SQL statements that execute a specific task. Their main use is in allowing common tasks to be easily replicated. The use of SQL server functions is similar to that of functions in mathematics, in that they correlate a series on inputs to a series of outputs. SQL Server supports two types of functions - user-defined and system.
##### 1 - User Defined function: User-defined functions are create by a user.
##### 2 - System Defined Function: System functions are built-in database functions. 

### [Triggers](https://github.com/serhatyamann/MS_SQL_SERVER/tree/main/)

#### A trigger is a special kind of Stored Procedure or stored program that is automatically fired or executed when some event (insert, delete and update) occurs.
If you write a trigger for an insert operation on a table, after firing the trigger, it creates a table named “INSERTED” in memory. Then it does the insert operation and then the statements inside the trigger executes. We can query the “INSERTED” table to manipulate or use the inserted row(s) from the trigger.
 
Similarly, if you write a trigger for a delete operation on a table, it creates a table in memory named “DELETED” and then deletes the row.


