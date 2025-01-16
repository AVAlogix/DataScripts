## 3. Find the century for the year
```sql

CREATE TABLE challenge (
    id INTEGER PRIMARY KEY,
    Year INTEGER
);

INSERT INTO challenge (
    id, Year) VALUES (1,1776), (2,2001), (3,1643), (4,1865), (5,1969);

SELECT * FROM challenge;

SELECT Year, CEIL(Year / 100) AS Century
FROM challenge;
