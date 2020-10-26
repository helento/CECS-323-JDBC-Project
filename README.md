# CECS 323 JDBC Project
Create a .sql file for the DDL and run this script to create the database, tables, etc. and for the DML used to populate the tables.
Write a JDBC program to support the following functions:
Create a simple menu to run all of the options below:
- List all writing groups
- List all the data for a group specified by the user .
(This includes all the data for the associated books and publishers.)
- List all publishers
- List all the data for a pubisher specified by the user.
(This includes all the data for the associated books and writing groups.)
- List all book titles
- List all the data for a single book specified by the user.
(This includes all the data for the associated publisher and writing group.)
- Insert a new book
- Insert a new publisher and update all book published by one publisher to be published by the new pubisher.
(This requirement is two separate operations. The idea is that a new publisher, (xyz) buys out an existing publisher (abc). After the new publisher is added to the database, all books that are currently published by abc will now be published by xyz.)
- Remove a single book specified by the user

# Requirements
- For all queries involving user input, you must use prepared statements
- You must be able to prove your results after each query
- Make sure to validate the data either through the java code or database constraints
- Make sure you handle any SQLExceptions that are thrown
- Use must use your NetBeans/Derby database for this project
- Make sure you have enough sample data to properly demonstrate your project
- The data can be fictional but it must be meaningful. I don't want to see Book One, Book Two, etc.
