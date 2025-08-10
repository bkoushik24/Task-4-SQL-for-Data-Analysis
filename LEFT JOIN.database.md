**e. LEFT JOIN**



**5. Customers who have never placed an order**



SELECT c.customer\_id, c.first\_name, c.last\_name

FROM customers c

LEFT JOIN orders o ON c.customer\_id = o.customer\_id

WHERE o.order\_id IS NULL;  



**Output:**



customer\_id	first\_name	last\_name

4	Ananya	Iyer

6	Carlos	Rodriguez

9	Fatima	Ali

&nbsp;                                                                                                                                   



