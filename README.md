# sql-project
Q1:- find the customer who has maximum number of order
<br>
select customer_name , count(customer_name)as count from myorders group by customer_name order by count desc limit 1;
<br>
Q2:- find top best customer based on sales 
