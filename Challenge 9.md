## 9. Just the unique values

```sql
CREATE TABLE challenge_5 (
    id INTEGER PRIMARY KEY,
    Name VARCHAR(10),
    Age INTEGER
);

INSERT INTO challenge_5 (
    id, Name, Age) VALUES (1,'Bob',21),(2,'Sam',19),(3,'Jill',18),(4,'Jim',21),
    (5,'Sally',19),(6,'Jess',20),(7,'Will',21);

SELECT * FROM challenge_5;

SELECT DISTINCT Age 
FROM challenge_5 AS Unique_age
ORDER BY Age;
