The user can find instructions on how to access the uploaded folder or file in this README.md file.

Contents

This repository includes the following diagrams in image format:

Entity-Relationship Diagram (ERD): This diagram shows the entities (tables) within the database and the relationships between them. It is essential for understanding the logical structure of the data and how different tables are connected.

Class Diagram: This diagram represents the object-oriented design of the project, illustrating the classes, their attributes, methods, and the relationships between them. It provides a blueprint for the software's structure and behavior.

Implementation Phase: This is the hands-on development stage where you build a functional application to manage categories, attributes, and products, following the design work completed in earlier phases.

File List

Database ERD.png

Class Diagram.png


Step 1: Extract the Project Files


Step 2: Open Command Prompt or Terminal


Step 3: Navigate to the Project Folder


Step 4: Run the Application


Once started, access the application at:

http://localhost:8080


product-management/

├── src/main/java/com/example/product_management/

│   ├── ProductManagementApplication.java  # ← MAIN APPLICATION FILE

│   ├── controller/                        # Web controllers

│   ├── model/                             # JPA entities

│   ├── repository/                        # Data repositories

│   └── service/                           # Business logic

├── src/main/resources/

│   ├── templates/                         # Thymeleaf HTML templates

│   └── application.properties             # Configuration

└── pom.xml                               # M dependencies


Once the application is running, you'll have access to:

A dashboard for managing product categories

Product inventory management system

Attribute configuration for different product types

Sample data to explore the features


Access Points

Main Application:       http://localhost:8080

Categories Management:  http://localhost:8080/categories

Products Management:    http://localhost:8080/products

Attributes Management:  http://localhost:8080/attributes

Database Console:       http://localhost:8080/h2-console

Database Information

Database Type: H2 In-Memory (resets on application restart)

Console URL: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb

Username: sa

Password: (leave empty)
