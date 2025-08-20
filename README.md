The user can find instructions on how to access the uploaded folder or file in this README.md file.

Contents

This repository includes the following diagrams in image format:

Entity-Relationship Diagram (ERD): This diagram shows the entities (tables) within the database and the relationships between them. It is essential for understanding the logical structure of the data and how different tables are connected.

Class Diagram: This diagram represents the object-oriented design of the project, illustrating the classes, their attributes, methods, and the relationships between them. It provides a blueprint for the software's structure and behavior.


Step 1: Extract the Project Files

First, extract the downloaded ZIP file to a location of your choice on your computer. You can right-click the ZIP file and select "Extract All" or use your preferred extraction tool.


Step 2: Open Command Prompt or Terminal

Windows Users: Press Windows Key + R, type cmd and press Enter

Mac Users: Open Spotlight Search (Cmd + Space), type "Terminal" and press Enter

Linux Users: Press Ctrl + Alt + T to open terminal


Step 3: Navigate to the Project Folder

Navigate to the extracted project folder: cd path/to/your/extracted/folder/product-management


Step 4: Run the Application

start the application with this command: mvnw.cmd spring-boot:run


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


Key Features

Dynamic Category Management: Create and manage product categories

Custom Attributes: Define category-specific attributes

Product Catalog: Complete product management with attributes

Database Console: Built-in H2 database management at /h2-console

Responsive UI: Bootstrap-based user interface


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
