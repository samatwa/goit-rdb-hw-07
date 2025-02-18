# goit-rdb-hw-07
1)
 SELECT 
	id, 
  	date, 
	 YEAR(date) as year,
  	MONTH(date) as month,
  	DAY(date) as day
FROM orders;

2)
SELECT
	id, 
    	date, 
    	DATE_ADD(date, INTERVAL 1 DAY) as next_day
FROM orders;

3)
SELECT 
	id, 
    	date, 
    	UNIX_TIMESTAMP(date) as timestamp_date
FROM orders;

