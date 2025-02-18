# goit-rdb-hw-07
1)
 SELECT 
	 id, 
  date, 
	 YEAR(date) as year,
  MONTH(date) as month,
  DAY(date) as day
FROM orders;
