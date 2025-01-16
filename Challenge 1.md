## Challenge 1 : Select each number as its opposite

CREATE TABLE challenge (
    id INTEGER PRIMARY KEY, 
    value INTEGER 
);

SHOW TABLES;

INSERT INTO challenge 
    (id, value) VALUES (1,-56),(2,76),(3,-84),(4,96),(5,-47);

SELECT * FROM challenge;

SELECT -value AS NewValue
FROM challenge;

## You can use the arithmetic negation operator (-) to return the opposite of the values in the value column.
