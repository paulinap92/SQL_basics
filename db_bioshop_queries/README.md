BIOSHOP Database Queries

This repository contains SQL scripts to manage and analyze data within the BIOSHOP database. The queries are designed to retrieve meaningful insights about customers, products, orders, and suppliers.
Available Operations

Below are the available SQL operations you can perform with this project:

    Retrieve all customers who have made purchases
    Extract a list of customers who have placed at least one order in the system.

    Calculate the aggregate quantity sold for each individual product
    Analyze sales data to calculate the total quantity sold for every product.

    Determine the total expenditure made by each customer
    Summarize the total amount spent by each customer across all their purchases.

    Display all suppliers associated with each product
    Retrieve details of suppliers responsible for delivering each product.

    Enumerate all products that have not yet been ordered
    List all products in the catalog that have not been included in any orders.

    Present the highest priced product available
    Identify the product with the highest price in the inventory.

    Present the lowest priced product available
    Identify the product with the lowest price in the inventory.

    Provide an overview of the total revenue generated from all orders
    Calculate the total revenue generated across all orders in the system.

    Display all products provided by a designated supplier
    Show all products supplied by a specific supplier based on their ID or name.

    Retrieve all orders placed within the preceding 7-day period
    Extract all orders made within the last 7 days to monitor recent activity.

File Structure

    1_bioshop_database_create.sql: Contains scripts for creating BIOSHOP DATABASE
    2_bioshop_tables_create.sql: Contains scripts for creating BIOSHOP TABLES
    3_bioshop_database_populate.sql: Contains scripts for populating BIOSHOP data
    4_bioshop_database_queries.sql: Contains queries for BIOSHOP data analysis

    README.md: Documentation for understanding and using the project.

How to Use

    Set Up the Database
        Import the sql files into your SQL server to create the database and tables and execute them in the order mentioned before.
        Ensure the database is named BIOSHOP.

    Execute Queries
        Use the queries in the queries.sql file to analyze the data and generate insights.

    Optional Enhancements
        Modify the scripts to add new data or customize queries for your specific needs.

Prerequisites

    SQL Server: Ensure you have a database server like MySQL, PostgreSQL, or SQL Server installed.
    SQL Client: Use tools like MySQL Workbench, pgAdmin, or any SQL IDE to execute the scripts.

Contribution

Feel free to fork the repository, submit issues, or create pull requests for any improvements or new features. Contributions are welcome!
License

This project is licensed under the MIT License. See the LICENSE file for details.
