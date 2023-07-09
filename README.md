# SQL-queires-set

This repository contains a set of SQL practice problems along with their solutions. Each problem is described below along with the corresponding SQL query to solve it.

## Problem 1: Creating a Customers Table

- **Prerequisite**: Understand creating tables in SQL / collections in MongoDB
- **Problem**: Create a `Customers` table / collection with the following fields: `id` (unique identifier), `name`, `email`, `address`, and `phone_number`.

Solution (SQL):
```sql
CREATE TABLE Customers (
  id INT PRIMARY KEY,
  name VARCHAR(255),
  email VARCHAR(255),
  address VARCHAR(255),
  phone_number VARCHAR(20)
);

## Problem 2: Inserting Data into the Customers Table

- **Prerequisite**: Understand inserting data into SQL tables / MongoDB collections
- **Problem**: Insert five rows / documents into the `Customers` table / collection with data of your choice.

Solution (SQL):
```sql
INSERT INTO Customers (id, name, email, address, phone_number)
VALUES
  (1, 'John Doe', 'johndoe@example.com', '123 Main St, City', '123-456-7890'),
  (2, 'Jane Smith', 'janesmith@example.com', '456 Elm St, Town', '987-654-3210'),
  (3, 'Mike Johnson', 'mikejohnson@example.com', '789 Oak Ave, Village', '555-123-4567'),
  (4, 'Sarah Williams', 'sarahwilliams@example.com', '321 Maple Rd, County', '888-999-0000'),
  (5, 'David Brown', 'davidbrown@example.com', '654 Pine Dr, State', '444-777-2222');
```

## Problem 3: Fetching All Data from the Customers Table

- **Prerequisite**: Understand basic data fetching in SQL / MongoDB
- **Problem**: Write a query to fetch all data from the `Customers` table / collection.

Solution (SQL):
```sql
SELECT * FROM Customers;
```

...

(Continue documenting the rest of the problems and their solutions)

```

Feel free to add more sections, formatting, or instructions as needed. The README is a versatile document that allows you to provide clear descriptions and solutions for each problem, making it easier for others to understand and work with the SQL practice problems

