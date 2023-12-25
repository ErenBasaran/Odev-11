Soru 1 Cevap :
(
select first_name from actor
)
union
(
select first_name from customer
); <br>
Soru 2 Cevap :
(
select first_name from actor
)
intersect
(
select first_name from customer
); <br>
Soru 3 Cevap :
(
select first_name from actor
)
except
(
select first_name from customer
); <br>
Soru 4 Cevap :
(
select first_name from actor
)
union all
(
select first_name from customer
); <br>
(
select first_name from actor
)
intersect all
(
select first_name from customer
); <br>
(
select first_name from actor
)
except all
(
select first_name from customer
); <br>
