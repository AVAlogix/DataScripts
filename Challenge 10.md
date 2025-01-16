## 10. Add the ages
```sql
CREATE TABLE challenge_10 (
    id INTEGER PRIMARY KEY,
    Name VARCHAR(10),
    Age INTEGER
);

INSERT INTO challenge_10 (
    id, Name, Age) VALUES (1,'Bob',21),(2,'Sam',19),(3,'Jill',18),(4,'Jim',21),
    (5,'Sally',19),(6,'Jess',20),(7,'Will',21);

SELECT * FROM challenge_10;

SELECT SUM(Age)
FROM challenge_10;
