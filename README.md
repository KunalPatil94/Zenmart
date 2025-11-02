# Zenmart
“Full Stack E-commerce Web Application using Spring Boot, React, and MySQL”


🛍️ ZenMart – Modern E-Commerce Web Application
🚀 Overview

ZenMart is a full-stack e-commerce web application designed to provide a smooth online shopping experience for both customers and administrators.
It demonstrates strong backend development skills in Spring Boot, REST APIs, and MySQL, combined with a modern frontend built in React.js.

This project showcases CRUD operations, secure authentication, role-based access, and database integration — making it ideal for showcasing backend and full-stack development capabilities.

🧠 Key Features

✅ User Authentication & Authorization – Login and Signup using Spring Security
✅ Product Management – Add, update, view, and delete products
✅ Cart & Checkout System – Add to cart, view cart, and place orders
✅ Admin Dashboard – Manage products and users dynamically
✅ Database Integration – Persistent storage using MySQL and JPA/Hibernate
✅ Responsive UI – Built with React.js for a clean and dynamic interface
✅ RESTful APIs – Well-structured endpoints for all core operations

🏗️ Tech Stack
💻 Backend

Java (Spring Boot Framework)

Spring Data JPA & Hibernate

MySQL Database

Maven

🌐 Frontend

React.js (Functional Components + Hooks)

HTML5, CSS3, JavaScript

Axios (API integration)

🧰 Tools & Others

VS Code / IntelliJ IDEA

Git & GitHub

Postman for API testing

⚙️ Installation & Setup
🗄️ Backend Setup (Spring Boot)
# Clone the repository
git clone https://github.com/<your-username>/ZenMart.git
cd ZenMart/backend

# Configure MySQL in application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/zenmart
spring.datasource.username=root
spring.datasource.password=yourpassword

# Run the Spring Boot app
mvn spring-boot:run

💻 Frontend Setup (React)
cd ../frontend
npm install
npm start


Your app will run on:
👉 Frontend: http://localhost:3000
👉 Backend: http://localhost:8080

🧩 API Endpoints (Examples)
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	User login
GET	/api/products	Fetch all products
POST	/api/products	Add new product (Admin only)
PUT	/api/products/{id}	Update product
DELETE	/api/products/{id}	Delete product
📸 Screenshots

(Add some UI screenshots here once ready)

🔐 Future Improvements

Payment Gateway Integration (Razorpay/Stripe)

Order Tracking

JWT Authentication

Cloud Deployment on Render / AWS

👨‍💻 Author

Kunal Patil
📧 [your.email@example.com
]
💼 [LinkedIn Profile Link]
🔗 GitHub: github.com/your-username

⭐ Acknowledgements

Spring Boot documentation

React official docs

MySQL community

Postman for API testing
