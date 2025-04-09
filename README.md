# answer.sql
use salesDB;
SELECT checkNumber, paymentDate, amount
FROM payments;


use salesDB;
SELECT orderDate, requiredDate, status
FROM orders
WHERE status = 'In Process'
ORDER BY orderDate DESC;


use salesDB;
SELECT firstName, lastName, email
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;


use salesDB;
SELECT *
FROM offices;


use salesDB;

SELECT productName, quantityInStock
FROM products
ORDER BY buyPrice ASC
LIMIT 5;

 
