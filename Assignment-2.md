

## What is the primary value add of relational databases over flat files?


- Ability to execute PHP code within the file 

- Ability to scan large amounts of data quickly✅

- Ability to execute JavaScript in the file

- Ability to quickly convert data to HTML

- Ability to store data in a format that can be sent across a network


## Which of the following is NOT a good rule to follow when developing a database model?


- Use integers as primary keys

- Never repeat string data in more than one table in a data model

- Each "object" in the application should be modeled as one or more tables

- Use a persons email address as their primary key✅

## If our user interface (i.e. like iTunes) has repeated strings on one column of the UI, how should we model this properly in a database:


- We put the string in the last row where it occurs and put the number of that row in the column all of the rest of the rows where the string occurs

- We put the string in the first row it occurs and then put that row number in the column all of the rest of the rows where the string occurs

- Encode the entire row as JSON and store it in a TEXT column in the database

- We make a table that maps the strings in the column to numbers and then use those numbers in the column✅

- We put the string in the first row where it occurs and then NULL in all of the other rows


## Which of the following is the label we give a column that the "outside world" uses to look up a particular row?


- Local key

- Remote key

- Foreign key

- Primary key

- Logical key✅

## What is the label we give to a column that is an integer and used to point to a row in a different table?

- Logical key

- Local key

- Primary key

- Remote key

- Foreign key✅

## What MySQL keyword is added to primary keys in a CREATE TABLE statement to indicate that the database is to provide a value for the column when records are inserted.


- INSERT_AUTO_PROVIDE

- ASSERT_UNIQUE

- PRIMARY

- AUTO_INCREMENT✅

## What is the SQL keyword that reconnects rows with foreign keys with the corresponding data in the table that the foreign key points to?


- COUNT

- CONNECT

- APPEND

- CONSTRAINT

- JOIN✅

## What happens when you JOIN two tables together without an ON clause?

- You get all of the rows of the left table in the JOIN and NULLs in all of the columns of the right table

- Leaving out the ON clause when joining two tables is an SQL syntax error

- The number of rows you get is the number of rows in the first table times the number of rows in the second table✅

- The rows of the left table are connected to the rows in the right table when their primary key matches

- You get no rows at all



## What does an "ON DELETE CASCADE" clause imply in a foreign key constraint in a MySQL CREATE TABLE statement?

- Whenever a row is deleted from the table, the other rows are scanned to insure that the logical key is unique and any duplicates are removed

- Whenever a row is deleted, it is moved into a table named "CASCADE"

- When a row in the parent table is deleted all the rows in a child table that point to that row via a foreign key are deleted✅

- When rows in a child table are deleted, the primary key of the corresponding row in the parent table is set to NULL

## Which of the following types of tables often are created without a primary key?

- Many-to-many✅

- One-to-many

- One-to-one

- B-Trees

- Hash Map


## When might one prefer the CHAR column type over VARCHAR?


- When the data is prose like a discussion comment versus a logical key

- When the data has widely varying lengths

- When the data is relatively short and almost always present✅

- When the data needs to be searched using a LIKE clause

## What is the built-in MySQL function that gives you the current time in an SQL statement?


- NOW()✅

- DATE(false)

- TODAY()

- CURR_DATE()

## Which of the following indexes would be best for fast look up for exact key matches but not so good for prefix lookups or sorting?
1 point

- HASH✅

- INDEX2

- BTREE

- EXACT

## Why is it a good idea to add "CONSTRAINT FOREIGN KEY" statements when creating database tables? (Check all that apply)
1 point

- So that you can specify default behaviors when records are deleted or updated

- So that prefix-based lookups perform well

- So that database modeling tools know the relationships between tables

- So that MySql knows which columns are foreign keys and which columns are just integers✅

## Question 15

When you add an index to a field in a database table, how are performance and storage affected?
1 point

- Read performance is the faster, insert performance is faster and extra storage is required

- Read performance is the same, insert performance is faster and no extra storage is required

- Read performance is faster, insert performance is the same and no extra storage is required

- Read performance is faster, insert performance is slower and extra storage is required✅- 


