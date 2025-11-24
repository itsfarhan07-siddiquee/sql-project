# sql-project
Q1:- find the customer who has maximum number of order
<br>
select customer_name , count(customer_name)as count from myorders group by customer_name order by count desc limit 1;
<br>
Q2:- find top best customer based on sales 
select customer_name, sum(sales)as sale from myorders group by customer_name order by sale desc limit 5;
<br>
Q3:- find top 5 customer based on quantity
<br>
select customer_name , sum(quantity)as qnt from myorders group by customer_name order by qnt desc limit 5;
<br>
Q4:-Change customer name into upper case
<br>
select *,upper(customer_name) from myorders;
<br>
