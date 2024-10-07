# ShoppingCart_SQL_Project

#### Overview
This project is an Online Shopping Cart system designed with PostgreSQL as the database backend and Java as the application layer. The system enables customers to browse products, add them to a cart, place orders, and manage payments. Managers have the ability to handle products, update stock, view orders, and manage both customer and product records.

#### Features

##### Customer Features:
- **Account Management:** Register and log in as a customer.
- **Product Browsing:** View available products.
- **Shopping Cart:** Add items to the shopping cart.
- **Order Placement:** Place orders with integrated payment handling.
- **Order History:** View order history and track order statuses.

##### Manager Features:
- **Authentication:** Log in with manager credentials.
- **Product Management:** Add, update, and delete products.
- **Stock Management:** Monitor and adjust stock levels.
- **Order Management:** View, update, and manage order statuses.
- **Customer Orders:** Access and manage all customer orders.

#### Technologies Used
- **PostgreSQL:** Relational database used for data storage.
- **Java:** Application layer to interact with the database.
- **PL/pgSQL:** Stored procedures and triggers for database operations and automation.

#### Database Structure
- **Customer:** Stores customer details (name, email, address).
- **Product:** Contains product information, including name, price, stock, and category.
- **Order:** Manages customer orders and their statuses.
- **Order_Item:** Tracks individual items within each order.
- **Manager:** Stores manager credentials for product and order management.
- **Payment:** Handles payment processing for orders.
- **Logs:** Automatically logs changes in Customer and Product records through triggers.

#### Stored Procedures and Triggers
- **Stored Procedures:** 
  - Manage operations for customer, product, and order records.
  - Include transaction handling with rollback functionality for error management.
  
- **Triggers:** 
  - Automatically log changes (insert, update, delete) for customer and product records in dedicated log tables.

#### Setup Instructions

##### Prerequisites
- **PostgreSQL:** Ensure that PostgreSQL is installed on your system.
- **Java Development Environment:** Set up an IDE like IntelliJ or Eclipse.
- **Git:** Use Git for version control to manage project development.

This setup provides a solid foundation for building and managing an Online Shopping Cart system with both customer and manager functionalities.
