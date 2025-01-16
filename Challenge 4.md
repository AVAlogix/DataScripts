## 4. Even or odd

```sql

CREATE TABLE challenge_4 (
    id INTEGER PRIMARY KEY,
    value INTEGER
);

INSERT INTO challenge_4
    (id, value) VALUES (1,4),(2,11),(3,57),(4,24),(5,47);

SELECT * FROM challenge_4;

SELECT value, 
    CASE 
        WHEN value % 2 = 0 THEN 'Even'
        ELSE 'Odd'
    END AS number_type
FROM challenge_4;
