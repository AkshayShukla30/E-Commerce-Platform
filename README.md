# 🛒 Full Stack E-Commerce Platform

A full-stack e-commerce application built with Spring Boot, React, and Python. The platform provides product management, user authentication, shopping cart, order processing, and AI-powered product search.

---

## Features

- User registration and login
- JWT-based authentication and authorization
- Product management
- Category management
- Shopping cart
- Order management
- Product search
- AI-powered image search
- Product recommendation support
- Responsive React frontend
- RESTful APIs
- Docker support
- CI/CD using GitHub Actions

---

## Tech Stack

### Backend

- Java 17
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA
- MySQL
- Maven

### Frontend

- React
- JavaScript
- Tailwind CSS
- Axios

### AI Service

- Python
- Flask
- OpenCV
- Machine Learning

### DevOps

- Docker
- Docker Compose
- GitHub Actions

---

## Project Structure

```text
fullstack-ecommerce-main
│
├── .github/
│   └── workflows/
│       ├── backend.yml
│       └── frontend.yml
│
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── herin/
│   │   │   │           └── ecommerce/
│   │   │   │               ├── config/
│   │   │   │               ├── controller/
│   │   │   │               ├── dto/
│   │   │   │               ├── exception/
│   │   │   │               ├── mapper/
│   │   │   │               ├── model/
│   │   │   │               ├── repository/
│   │   │   │               ├── service/
│   │   │   │               └── EcommerceApplication.java
│   │   │   └── resources/
│   │   └── test/
│   ├── Dockerfile
│   └── pom.xml
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── Dockerfile
│   ├── nginx.conf
│   └── package.json
│
├── ml_backend/
│   ├── static/
│   ├── app.py
│   ├── model.py
│   ├── search.py
│   ├── upload.py
│   ├── build_index.py
│   ├── Dockerfile
│   └── requirement.txt
│
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

## Backend Modules

- Authentication
- User Management
- Product Management
- Category Management
- Order Management
- Shopping Cart
- REST APIs

---

## Frontend

- Home Page
- Product Listing
- Product Details
- Shopping Cart
- Authentication
- Checkout
- Responsive UI

---

## AI Service

- Image upload
- Feature extraction
- Similar product search
- Product recommendation

---

## Running the Project

### Clone Repository

```bash
git clone https://github.com/AkshayShukla30/fullstack-ecommerce.git
```

### Start using Docker

```bash
docker compose up --build
```

---

## Backend

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

---

## Frontend

```bash
cd frontend
npm install
npm start
```

---

## AI Service

```bash
cd ml_backend
pip install -r requirement.txt
python app.py
```

---

## Future Improvements

- Payment Gateway Integration
- Wishlist
- Product Reviews
- Admin Dashboard
- Order Tracking
- Email Notifications
- Recommendation Improvements

---

## Author

**Akshay Shukla**

---

## 📬 Contact

📧 Email: <a href="mailto:akshayshukla466@gmail.com">akshayshukla466@gmail.com</a>

💼 LinkedIn: 

🐙 GitHub:
