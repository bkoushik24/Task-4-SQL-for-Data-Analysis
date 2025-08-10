**f. Subquery**



**6. Products with price above average**



SELECT product\_id, product\_name, price

FROM products

WHERE price > (

&nbsp;   SELECT AVG(price) FROM products

)                                                                                                                                                                               

ORDER BY price DESC;



**Output:**



product\_id	product\_name	price

1	Laptop Pro X	        1500.00

2	Smartphone Z Max	900.00

3	Wireless Headset	120.00

4	Office Chair	        250.00

5	Coffee Maker	        80.00

6	Tablet Air 11	        600.00

7	Gaming Monitor	        350.00



