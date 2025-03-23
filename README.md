# answer.sql CREATE TABLE payments (
    checkNumber Vin(50),
    paymentDate DATE,
    amount DECIMAL(10, 2)
);

CREATE TABLE orders (
    orderDate 2023-10-20,
    requiredDate 2023-10-27,
    status delivered(20)
);

CREATE TABLE employees (
    employeeNumber INTEGER PRIMARY KEY, -- 01001
    firstName King(50),
    lastName Vihnie(50),
    email omugavinich@gmail.com(100)
);

CREATE TABLE products (
    productName Master(100),
    quantityInStock INT,
    buyPrice DECIMAL(10, 2)

INSERT INTO payments (checkNumber, paymentDate, amount) VALUES
('CH123', '2023-10-26', 150.00),
('CH456', '2023-10-27', 200.50),
('CH789', '2023-10-28', 75.25);

INSERT INTO orders (orderDate, requiredDate, status) VALUES
('2023-10-20', '2023-10-30', 'In Process'),
('2023-10-22', '2023-11-01', 'Shipped'),
('2023-10-25', '2023-11-05', 'In Process');

INSERT INTO employees (employeeNumber, firstName, lastName, email) VALUES
(101, 'Alice', 'Smith', 'alicesmith@gmail.com'),
(102, 'Bob', 'Johnson', 'bobjohnson@gmail.com'),
(103, 'Charlie', 'Williams', 'charliewilliams@gmail.com');

INSERT INTO products (productName, quantityInStock, buyPrice) VALUES
('Laptop', 10, 800.00),
('Mouse', 50, 15.50),
('Keyboard', 25, 50.00);



