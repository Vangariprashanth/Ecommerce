# Ecommerce
This repository contains the backend API for an e-commerce platform where users can browse products, manage orders, and receive shipments. The system supports user registration, product inventory management, and order processing, built with Spring Boot and SQL Server.

Tech Stack:
1. Angular js - The front end website.
2. Spring Boot - The back-end API server.
3. SQL Server - The database engine.


-------------
Entities
-------------
User
	1. ID
	2. Username
	3. Encrypted password
	4. Email
	5. First name
	6. Last name

Address
	1. ID
	2. User
	3. Address Line 1
	4. Address Line 2
	5. City
	6. Country
	7. Post Code
	8. Active?

Product
	1. ID
	2. Name
	3. Short Description
	4. Long Description
	5. Price

Inventory
	1. Product
	2. In stock quantity

Order
	1. ID
	2. User
	3. Address
	4. Products+quantities



