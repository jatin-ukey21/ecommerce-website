# 🛍️ E-Commerce Website

A **full-stack e-commerce application** built with:
- **Frontend:** ReactJS (for user interface and admin panel)
- **Backend:** Java Spring Boot (for REST APIs and business logic)
- **Database:** MySQL / MongoDB (for product, user, and order data)

---

## 📘 Table of Contents
1. [Project Overview](#-project-overview)
2. [Tech Stack](#-tech-stack)
3. [Schema Diagram](#-schema-diagram)
4. [Features](#-features)
5. [Project Structure](#-project-structure)
6. [Setup & Run Instructions](#-setup--run-instructions)
7. [Screenshots](#-screenshots)
   - [User Interface](#-user-interface-16-images)
   - [Admin Interface](#-admin-interface-5-images)
   - [Backend API (Swagger)](#-backend-api-swagger-11-images)
8. [Future Enhancements](#-future-enhancements)
9. [Author](#-author)

---

## 🧠 Project Overview

This project is a **modern online shopping platform** that allows users to browse products, add them to the cart, and complete purchases, while the admin can manage products, categories, and inventory.  
It demonstrates a **complete full-stack workflow**, from RESTful backend APIs to a responsive ReactJS frontend.

---

## ⚙️ Tech Stack

**Frontend**
- ReactJS
- Axios for API communication
- React Router
- Tailwind CSS / Bootstrap

**Backend**
- Spring Boot 3.x
- Spring Data JPA / MongoTemplate
- Lombok, ModelMapper / MapStruct
- JWT Authentication
- RESTful APIs with Swagger UI

**Database**
- MySQL / MongoDB

**Other Tools**
- IntelliJ IDEA (backend)
- VS Code (frontend)
- Git & GitHub for version control

---

## 🗺️ Schema Diagram

> The schema diagram below represents how the entities (Users, Products, Orders, etc.) are related in the database.

![Schema Diagram](./images/schema.png)

> Replace the path above with your actual schema image path if different.

---

## ✨ Features

### 👤 User Side
- Register, login, and browse products  
- Add items to cart and checkout  
- View order history  
- Responsive UI for all devices  

### 🧑‍💼 Admin Side
- Add, update, and delete products  
- Manage categories and users  
- View all orders and analytics  
- Dashboard for product and order management  

### ⚙️ Backend
- RESTful APIs with JWT authentication  
- Product filtering and pagination  
- Swagger documentation (`/swagger-ui/index.html`)  
- Secure API access and validation  

---

## 📂 Project Structure

```
ecommerce-website/
│
├── eCommersApp-frontend/     → ReactJS frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── eCommersApp-backend/      → Spring Boot backend
│   ├── src/
│   ├── pom.xml
│   └── ...
│
└── README.md
```

> If your folder names differ, update them accordingly in this README.

---

## 🚀 Setup & Run Instructions

### 🖥️ Backend (Spring Boot)

1. Navigate to backend:
   ```bash
   cd eCommersApp-backend
   ```

2. Build and run:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

3. Access the backend at:  
   `http://localhost:8080`

4. Swagger UI available at:  
   `http://localhost:8080/swagger-ui/index.html`

---

### 🌐 Frontend (React)

1. Navigate to frontend:
   ```bash
   cd eCommersApp-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the React app:
   ```bash
   npm start
   ```

4. Access the app at:  
   `http://localhost:3000`

---

## 🖼️ Screenshots

> Create an `images/` folder in the repo root, with subfolders `user/`, `admin/`, and `backend/`.  
> Place screenshots as numbered files (e.g., `1.png`, `2.png`, ...).  
> Update filenames or paths below if your names differ.

### 🧩 User Interface (16 images)

Showcasing user-facing features like product browsing, cart, checkout, and order history.

![User Screenshot 1](./images/user/1.png)
![User Screenshot 2](./images/user/2.png)
![User Screenshot 3](./images/user/3.png)
![User Screenshot 4](./images/user/4.png)
![User Screenshot 5](./images/user/5.png)
![User Screenshot 6](./images/user/6.png)
![User Screenshot 7](./images/user/7.png)
![User Screenshot 8](./images/user/8.png)
![User Screenshot 9](./images/user/9.png)
![User Screenshot 10](./images/user/10.png)
![User Screenshot 11](./images/user/11.png)
![User Screenshot 12](./images/user/12.png)
![User Screenshot 13](./images/user/13.png)
![User Screenshot 14](./images/user/14.png)
![User Screenshot 15](./images/user/15.png)
![User Screenshot 16](./images/user/16.png)

---

### 🧑‍💼 Admin Interface (5 images)

Showcasing admin panel features like product management, dashboard, and analytics.

![Admin Screenshot 1](./images/admin/1.png)
![Admin Screenshot 2](./images/admin/2.png)
![Admin Screenshot 3](./images/admin/3.png)
![Admin Screenshot 4](./images/admin/4.png)
![Admin Screenshot 5](./images/admin/5.png)

---

### ⚙️ Backend API (Swagger) (11 images)

Showcasing backend endpoints, entities, and Swagger documentation.

![Backend Screenshot 1](./images/backend/1.png)
![Backend Screenshot 2](./images/backend/2.png)
![Backend Screenshot 3](./images/backend/3.png)
![Backend Screenshot 4](./images/backend/4.png)
![Backend Screenshot 5](./images/backend/5.png)
![Backend Screenshot 6](./images/backend/6.png)
![Backend Screenshot 7](./images/backend/7.png)
![Backend Screenshot 8](./images/backend/8.png)
![Backend Screenshot 9](./images/backend/9.png)
![Backend Screenshot 10](./images/backend/10.png)
![Backend Screenshot 11](./images/backend/11.png)

---

## 🚧 Future Enhancements

- Integrate payment gateway (Stripe / Razorpay)  
- Add product reviews and ratings  
- Implement wishlist and coupons  
- Enable email notifications  
- Add admin dashboard analytics  

---

## 👨‍💻 Author

**Jatin Ukey**  
📍 Nagpur, India  
📧 [jatinukey21@gmail.com](mailto:jatinukey21@gmail.com)  
🔗 [GitHub](https://github.com/jatin-ukey21) | [LinkedIn](https://linkedin.com/in/jatin-ukey21)

---

🛒 *Thank you for exploring this project!*

