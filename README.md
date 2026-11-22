# ZaZa - ONLINE FOOD DELIVERY SYSTEM (CORE JAVA)

# PROJECT OVERVIEW:

ZaZa is a console-based Online Food Delivery System developed using Core Java and Object-Oriented Programming (OOP) principles. The application provides separate Admin and Customer modules to manage restaurant operations, food items, customer activities, and order processing. It follows a menu-driven approach that allows users to interact with the system through console inputs and perform essential food delivery operations.

# DESCRIPTION:

The application is structured using Java packages to separate data models, business logic, and application execution.

The Model package contains classes representing entities such as FoodItem, User, Customer, and Restaurant. The Service package handles business operations, including restaurant management, menu management, cart operations, order processing, and delivery assignments. The Main package contains the application entry point and menu-driven interface through which users interact with the system.

The application uses Object-Oriented Programming concepts to organize functionality, maintain code structure, and manage different application entities.

# WHAT THIS APPLICATION DOES:

This application simulates an online food delivery system through a console-based interface.

It allows administrators to manage restaurants and food items.

It enables administrators to view customer orders.

It supports delivery person management and order assignments.

It allows customers to select or register within the application.

It enables customers to browse restaurant menus.

It provides cart operations to add and remove food items.

It allows customers to place orders and track order status.

# FEATURES:
 ## ADMIN MODULE:
  - Manage Restaurants and Food Items.
  
  - View all orders.
  
  - Manage Delivery Persons and assign them to orders.
    
  ## CUSTOMER MODULE:
  
  - Register/Select customers.
  
  - Browse restaurant menus.
  
  - Manage Cart (add/remove items).
    
  - Place orders and track status.

# HOW TO RUN:
- Open your terminal.

- Navigate to the project root directory.

- Compile the code:
   ```bash
   javac -d bin src/com/zaza/model/*.java src/com/zaza/service/*.java src/com/zaza/main/*.java
   ```
   
- Run the application:
   ```bash
   java -cp bin com.zaza.main.ZaZaApp
   ```

# PROJECT STRUCTURE:
- `com.zaza.model`: Contains entity classes like `FoodItem`, `User`, `Customer`, `Restaurant`, etc.

- `com.zaza.service`: Contains business logic for handling operations.

- `com.zaza.main`: Main entry point with the menu-driven driver.
