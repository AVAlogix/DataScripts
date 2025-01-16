## 8. Who needs a passport
```sql
CREATE TABLE challenge_8 (
    id INTEGER PRIMARY KEY,
    Name VARCHAR(20),
    Country TEXT
);

INSERT INTO challenge_8
    (id, Name, Country) VALUES (1,'Bob Smith','United States'),(2,'Jim Jones','China'),
    (3,'Sam White','Japan'),(4,'Jess Black','Canada'),(5,'Will Wilson','Germany'),
    (6,'Wilson Scott','England'),(7,'Scott Daniels','France'),
    (8,'Daniel Jackson','Canada'),(9,'Jack Johnson','United States');

SELECT * FROM challenge_8;

SELECT Name, Country
FROM challenge_8
WHERE Country NOT IN ('Canada', 'United States');
