 Product Catalog Application
A full-stack web application for managing products, built with:

Spring Boot (Java) — backend REST API and MVC views

Angular — frontend single-page application

H2 in-memory database for persistence

📁 Project Structure
bash
Copy
Edit
product_catalog/
│
├── products-service/       # Spring Boot backend
│   └── src/main/java/...   # REST APIs + MVC Controller
│
└── angular_product/        # Angular frontend
    └── src/                # Angular SPA
🚀 Features
🖥 Backend (Spring Boot)
RESTful API to manage products

MVC interface using Thymeleaf (/index)

Example data seeded on startup

Product operations:

Add

Delete

List all

View by ID

🌐 Frontend (Angular)
Product list view with HTTP integration

Basic CRUD operations using REST API

Responsive UI using Angular components

📚 Technologies Used
Layer	Technology
Backend	Spring Boot, Spring Data JPA
Frontend	Angular 19
Database	H2 in-memory
Build	Maven (backend), Angular CLI (frontend)

🛠️ How to Run
✅ Backend (Spring Boot)
Navigate to products-service/

REST endpoints:

GET http://localhost:8080/products

GET/DELETE http://localhost:8080/products/{id}

MVC view:

http://localhost:8080/index

✅ Frontend (Angular)
Navigate to angular_product/

Install dependencies:

npm install
Run development server:

ng serve
Access:


http://localhost:4200
🔁 Sample Data
On app startup, the backend automatically creates:

Name	Price	Quantity
Computer	5400	11
Printer	1299	11
Smart Phone	12000	33

🧪 API Endpoints
Method	Endpoint	Description
GET	/products	Get all products
GET	/products/{id}	Get product by ID
DELETE	/products/{id}	Delete product by ID

📝 Author
Khawla Lamsiyeh
🔗 GitHub: @lamsiyehkhawla
