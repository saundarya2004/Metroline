# 🚇 MetroLine — Metro Ticket Booking & Management System

**MetroLine** is a full-stack web application for managing metro routes, stations, users, and ticket bookings. The system provides separate functionalities for **Users and Administrators**, with secure authentication and a React-based frontend connected to a Spring Boot REST API.

---

## 📌 Project Overview

MetroLine simplifies the metro ticket booking process by allowing users to search for routes between stations, view journey details, calculate fares, book tickets, and manage their booking history.

The application follows a layered backend architecture using **Spring Boot, Spring Data JPA, and Hibernate**, with **MySQL** for persistent data storage.

Authentication and authorization are implemented using **JWT (JSON Web Token)** with role-based access for Users and Administrators.

---

## ✨ Features

### 👤 User Features

* User registration and login
* JWT-based authentication
* Search metro routes between stations
* View available route information
* View intermediate stops
* View journey distance
* View estimated travel time
* Calculate applicable fare
* Book metro tickets
* View booking/ticket history
* Cancel bookings

### 🛠️ Admin Features

* Admin authentication
* Role-based access control
* Manage metro-related data through secured backend endpoints
* Manage stations, routes, and booking-related information

### 🔐 Security

* JWT-based authentication
* Role-based authorization
* Protected backend endpoints
* Custom JWT authentication filter

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │     React.js UI     │
                    │                     │
                    │  React Router       │
                    │  Axios              │
                    └──────────┬──────
```
