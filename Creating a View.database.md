**h. Creating a View**



**8. View for monthly sales**



CREATE VIEW monthly\_sales AS

SELECT DATE\_FORMAT(order\_date, '%Y-%m') AS month, SUM(total\_amount) AS total\_sales

FROM orders

GROUP BY DATE\_FORMAT(order\_date, '%Y-%m');



SELECT \* FROM monthly\_sales;



**Output:**



order\_id	order\_date	total\_amount

1	2025-06-05 10:20:00	750.00

2	2025-06-18 14:10:00	1200.00

3	2025-07-01 09:45:00	900.00

4	2025-07-15 15:30:00	1500.00

5	2025-08-02 11:15:00	600.00









