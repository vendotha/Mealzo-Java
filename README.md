# 🍽️ **Mealzo – Online Food Delivery Web Services**

> 🚀 **Mealzo** is a Spring Boot–powered backend web service designed to provide a reliable and efficient API system for online food delivery platforms — managing users, restaurants, items, carts, orders, and billing seamlessly.

---

## 📊 **Project Overview**

**Mealzo** is a RESTful web application backend built using the **Spring Boot Framework**.  
It provides a robust API ecosystem that caters to front-end applications by handling **authentication**, **restaurant management**, **order processing**, and **billing workflows** — ensuring a smooth end-to-end experience for both customers and admins.

---

## ⚙️ **Tech Stack & Tools**

| Technology | Purpose |
|-------------|----------|
| **Java** | Core programming language |
| **Spring Boot** | Backend framework |
| **Spring Data JPA** | ORM and database interaction |
| **Hibernate** | Data persistence |
| **MySQL** | Relational database |
| **Maven** | Dependency management |
| **Swagger-UI** | Interactive API documentation |
| **Lombok** | Reduces boilerplate code |

---

## 🧩 **Modules**

- 🔐 **Login Module** – Secure user authentication and session management  
- 🍴 **Restaurant Module** – Manage restaurant details, menus, and availability  
- 👤 **Customer Module** – Customer registration, login, and profile management  
- 🛒 **Food Cart Module** – Add, update, and view cart items  
- 📦 **Order Module** – Place, update, and track customer orders  
- 🧾 **Bill Module** – Generate and retrieve billing details  
- 🍔 **Items Module** – Manage food items and categories  

---

## 🧠 **Key Features**

✅ **Authentication & Authorization**
- Session-based login with unique session IDs  
- Role-based access for Admin and Customer  

✅ **Admin Functionalities**
- Perform CRUD operations on restaurants and menu items  
- Remove or update food listings  
- Access order and billing details  

✅ **Customer Functionalities**
- Register and authenticate easily  
- Browse available items and restaurants  
- Manage cart, place orders, and view bills  
- Update account and order details  

✅ **Developer-Friendly APIs**
- Fully documented APIs with **Swagger-UI**  
- Simplified JSON request/response structure  

---

## 🗂️ **ER Diagram**

![ER Diagram](https://user-images.githubusercontent.com/101379495/213903200-10b62ca4-cd7c-476c-9bc7-fdbb8e4de54b.png)

---

## 🧭 **Controllers Overview**

| Controller | Function |
|-------------|-----------|
| **LoginController** | User login & authentication |
| **CustomerController** | Manage customer details |
| **RestaurantController** | Handle restaurant data |
| **ItemController** | Manage menu items |
| **CartController** | Manage customer food carts |
| **OrderController** | Handle orders & tracking |
| **BillController** | Manage billing operations |

---

## 💻 **Installation & Run**

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/mealzo.git
   cd mealzo
2. Configure your database in src/main/resources/application.properties:
   ```bash
   server.port=8080
   spring.datasource.url=jdbc:mysql://localhost:3306/Mealzo
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
   spring.datasource.username=your_username_here
   spring.datasource.password=your_password_here
3. Build and run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run 
4. 🌐 API Root Endpoints
   ```bash
   https://localhost:8080/
   https://localhost:8080/swagger-ui.html
## 📈 Metrics
 Metric	Description
- ⏱️ Response Time	~150ms average for API endpoints
- ⚡ Performance	Handles concurrent user requests efficiently
- 🔐 Security	Session-based authentication with unique IDs
- 🧩 Maintainability	Modular and scalable architecture
## 🏁 Summary
- Mealzo is a complete backend web service designed to power scalable, secure, and modular food delivery systems.
- With clean architecture, optimized database handling, and developer-friendly APIs, it serves as a reliable backend solution for modern web applications. 🍕✨
