## Example walkthrough for assignment

Perform the instructions below and enter the code you get into the following assignment. (Hint: starts with 493)
Specifications

**First, create a MySql database or use an existing database (make sure to use a UTF8 character set) and then create a table in the database called "Ages":**

```
CREATE TABLE Ages ( 
  name VARCHAR(128), 
  age INTEGER
)

```

Then make sure the table is empty by deleting any rows that you previously inserted, and insert these rows and only these rows with the following commands:
## Sample Data

```
DELETE FROM Ages;
INSERT INTO Ages (name, age) VALUES ('Zahra', 34);
INSERT INTO Ages (name, age) VALUES ('Olufunke', 23);
INSERT INTO Ages (name, age) VALUES ('Choire', 38);
INSERT INTO Ages (name, age) VALUES ('Makenna', 32);
INSERT INTO Ages (name, age) VALUES ('Ula', 16);
INSERT INTO Ages (name, age) VALUES ('Garren', 40);

```

For the assignment use the data on your individual autograder page, not the sample data above.

Once the inserts are done, run the following SQL command:

```
SELECT sha1(CONCAT(name,age)) AS X FROM Ages ORDER BY X

```

Find the first row in the resulting record set and enter the long string that looks like 254c6127cdbc4c38e065317667340e8b0950046f (this is just a sample string). Use the hint  as a guide. 

## Sample data output:
![image](https://user-images.githubusercontent.com/81081105/174044619-8897417e-1853-4d56-8170-504203a5b5b6.png)
