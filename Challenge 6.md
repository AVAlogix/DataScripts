## 6. Return a greeting string
```sql
CREATE TABLE challenge_6 (
    id INTEGER PRIMARY KEY,
    Name VARCHAR(10)
);

INSERT INTO challenge_6 (
    id, Name) VALUES (1,'Bob'),(2,'Sam'),(3,'Jill'),(4,'Jim'),
    (5,'Sally'),(6,'Jess'),(7,'Will');

SELECT * FROM challenge_6;

SELECT CONCAT('Hi, ', Name, '! How are you today?') AS Greeting
FROM challenge_6;
