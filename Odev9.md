- City tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```SQL
SELECT city, country from city
INNER JOIN country ON country.country_id = city.country_id;
```
- Customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```SQL
SELECT payment_id , first_name, last_name from customer
INNER JOIN payment ON payment.customer_id=customer.customer_id;
```
- Customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
```SQL
SELECT first_name, last_name, rental_id FROM rental
INNER JOIN customer ON customer.customer_id = rental.customer_id;
```