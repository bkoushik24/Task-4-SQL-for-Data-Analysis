**i. Index for Optimization**



**9. Create index on order\_date**



CREATE INDEX idx\_order\_date ON orders(order\_date);



SELECT \* FROM orders

WHERE order\_date BETWEEN '2025-07-01' AND '2025-07-31';





**Output:**



Table	Non\_unique	Key\_name	Seq\_in\_index	Column\_name	Collation	Cardinality	Index\_type

orders	   1	     idx\_order\_date	     1	        order\_date	    A	            0	          BTREE









