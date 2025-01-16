## 7. Find the best selling products
```sql
CREATE TABLE challenge_7 (
    id INTEGER PRIMARY KEY,
    Name VARCHAR(10),
    Amount_sold INTEGER
);

INSERT INTO challenge_7
    (id, Name, Amount_sold) VALUES (1,'Cup',11),(2,'Saucer',22),(3,'Plate',46),(4,'Fork',34),
    (5,'Spoon',45),(6,'Knife',78),(7,'Mug',23),(8,'Glass',64),(9,'Tumbler',24);

SELECT * FROM challenge_7;

SELECT Name, Amount_sold
FROM challenge_7
ORDER BY Amount_sold DESC
LIMIT 5;
