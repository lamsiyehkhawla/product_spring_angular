# 🛠️ Products Service — Spring Boot Backend

A simple RESTful and MVC backend for managing a product catalog. Built using **Spring Boot**, **Spring Data JPA**, and **H2** in-memory database.

---

## 📦 Features

- 📃 REST API to manage products
- 🌐 MVC interface using Thymeleaf at `/index`
- 🗃️ H2 in-memory database for quick setup
- 🧪 Sample data preloaded on startup

---

## 📁 Structure

products-service/
├── entities/ # Product entity
├── repository/ # JPA repository
├── web/ # REST API + MVC controller
└── WebMvcProductsApplication.java


---

## 🚀 How to Run

### 📌 Prerequisites

- Java 17+
- Maven

Endpoints
🧩 REST API
Method	Endpoint	Description
GET	/products	Get all products
GET	/products/{id}	Get product by ID
DELETE	/products/{id}	Delete product by ID

🖥 MVC Web Interface
URL	Description
/index	View product list
/deleteProduct?id={id}	Delete a product

 Author
Khawla Lamsiyeh
GitHub: @lamsiyehkhawla
