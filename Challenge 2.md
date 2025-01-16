##2. Select all the divisions that have had revenue this year
```sql

CREATE TABLE challenge (
    Division_id INTEGER,
    Year INTEGER,
    Revenue INTEGER
);

INSERT INTO challenge (
    Division_id, Year, Revenue) VALUES (1,2018,60),(1,2021,40),(1,2020,70),
    (2,2021,-10),(3,2018,20),(3,2016,40),(4,2021,50);

SELECT * FROM challenge;

SELECT Division_id 
FROM challenge
WHERE Year = 2021
AND Revenue >= 0;
