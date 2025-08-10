**d. INNER JOIN** 



**4. Orders with customer details**



SELECT o.order\_id, c.first\_name, c.last\_name, o.total\_amount

FROM orders o

INNER JOIN customers c ON o.customer\_id = c.customer\_id

ORDER BY o.total\_amount DESC;     



**Output:**



order\_id	first\_name	last\_name	total\_amount

12	Ahmed	Khan	1500.00

5	Priya	Sharma	1250.00

8	John	Smith	900.00

3	Sarah	Lee	750.00

10	Emily	Davis	720.00

6	Ravi	Kumar	600.00

