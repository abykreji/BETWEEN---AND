## Excercise
##### Who between the ages of 30 and 50 has an income less than 50 000?

```python
SELECT *
FROM customers
WHERE age BETWEEN 30 AND 50 AND income < 50000;
```

##### What is the average income between the ages of 20 and 50? 
```python
SELECT AVG(income)
FROM customers
WHERE age BETWEEN 20 AND 50;
```