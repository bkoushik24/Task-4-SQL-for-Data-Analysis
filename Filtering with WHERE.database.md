**b. Filtering with WHERE**



**2. Orders above $500**

SELECT order\_id, customer\_id, order\_date, total\_amount

FROM orders

WHERE total\_amount > 500

ORDER BY total\_amount DESC;



**Output:**



order\_id	customer\_id	order\_date	total\_amount

12	3	2025-07-15 14:22:10	1500.00

5	8	2025-06-28 10:15:35	1250.00

8	2	2025-07-01 18:45:02	900.00

3	1	2025-06-15 09:05:20	750.00



