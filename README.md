# airbnb-clone-backend
A scalable Airbnb-like backend built with Node.js, TypeScript, and microservices architecture including user, property, and booking services with JWT authentication.
# 🏠 Airbnb Backend (Microservices Architecture)

This project is a scalable backend system inspired by Airbnb, developed using Node.js, TypeScript, and a microservices architecture. It is designed to handle core functionalities such as user management, property listings, and booking management in a modular and efficient way.

The system focuses on scalability, performance, and secure API design using modern backend technologies.

---

## 🚀 Features

- 🧩 Microservices architecture (User, Property, Booking services)  
- 🔐 Secure authentication using JWT  
- 📡 API Gateway for centralized routing and request handling  
- 📅 Booking system with conflict-free date validation  
- ⚡ High performance using Redis caching  
- 🔄 Background job processing with BullMQ  
- 🗄️ Multi-database support (MySQL & MongoDB)  
- 📈 Scalable and modular backend design  

---

## 🛠️ Tech Stack

- **TypeScript** – Strongly typed JavaScript  
- **Node.js** – Backend runtime  
- **Express.js** – Web framework  
- **MySQL** – Relational database  
- **MongoDB** – NoSQL database  
- **Redis** – Caching and queue management  
- **BullMQ** – Background job processing  
- **JWT (JSON Web Token)** – Authentication  

---

## 🧩 Microservices Overview

### 👤 User Service
- User registration and login  
- JWT authentication  
- Profile management  

### 🏡 Property Service
- Add and manage property listings  
- Property details and availability  

### 📅 Booking Service
- Create and manage bookings  
- Prevent overlapping reservations  
- Ensure date availability  

---

## 🌐 API Gateway

- Central entry point for all client requests  
- Handles routing to respective microservices  
- Implements authentication and rate limiting  

---

## 📂 Project Structure
airbnb-backend/
│── api-gateway/ # API Gateway service
│── user-service/ # User microservice
│── property-service/ # Property microservice
│── booking-service/ # Booking microservice
│── shared/ # Shared utilities and configs
│── docker-compose.yml # (Optional) container setup


---

## ⚙️ How It Works

- Client sends request to API Gateway  
- Gateway authenticates and routes request  
- Microservices process the request independently  
- Booking service ensures no date conflicts  
- Redis caches frequently accessed data  
- BullMQ handles background tasks asynchronously  

---

## 🎯 Objective

The main objectives of this project are:

- To design scalable backend systems using microservices  
- To implement secure authentication and API handling  
- To understand distributed system architecture  
- To improve backend performance using caching and queues  
- To build real-world production-level backend systems  


## 📌 Future Enhancements

- 🐳 Docker containerization  
- ☁️ Deployment on AWS / cloud platforms  
- 📊 Monitoring and logging (Prometheus, Grafana)  
- 🔎 Advanced search and filtering  
- 💳 Payment integration  

---

## 🤝 Contribution

Feel free to fork and enhance the project.

---

## 📄 License

This project is licensed under the MIT License.
