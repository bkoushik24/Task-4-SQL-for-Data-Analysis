**c. Aggregation + GROUP BY**



**3. Total sales per customer**



SELECT customer\_id, SUM(total\_amount) AS total\_spent

FROM orders

GROUP BY customer\_id

ORDER BY total\_spent DESC;



**Output**:



customer\_id	total\_spent

3	3450.00

1	2750.00

8	2100.00

2	1950.00

5	1100.00

6	950.00

4	750.00



