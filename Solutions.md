# SQL Challenge 10

This SQL script demonstrates table creation, data insertion, and a query to calculate the sum of ages.

```sql
-- Create the challenge_10 table
CREATE TABLE challenge_10 (
    id INTEGER PRIMARY KEY,
    Name VARCHAR(10),
    Age INTEGER
);

-- Insert data into the challenge_10 table
INSERT INTO challenge_10 (id, Name, Age) 
VALUES 
    (1, 'Bob', 21),
    (2, 'Sam', 19), 
    (3, 'Jill', 18), 
    (4, 'Jim', 21),
    (5, 'Sally', 19), 
    (6, 'Jess', 20), 
    (7, 'Will', 21);

-- Select all data from the challenge_10 table
SELECT * FROM challenge_10;

-- Calculate the sum of the ages in the challenge_10 table
SELECT SUM(Age)
FROM challenge_10;
