# 🚇 MetroLine

### Smart Metro Management & Journey Assistance Platform

MetroLine is a full-stack web application designed to enhance the metro commuting experience through **intelligent journey assistance, automated station notifications, route management, and digital metro card services**.

The project demonstrates the development of a real-world, modular application using **Java, Spring Boot, RESTful APIs, React.js, and SQL/Oracle**, with a focus on maintainable architecture, database-driven operations, automation, and user experience.

---

## 📌 Problem Statement

Metro passengers often need to manage multiple aspects of their journey, including identifying the correct route, monitoring upcoming stations, keeping track of their metro card balance, and managing transactions.

MetroLine aims to bring these services together into a **single, user-friendly platform**, reducing manual effort and providing timely journey assistance.

---

## 💡 Solution

MetroLine provides an integrated platform where users can:

- Plan and manage metro journeys
- Access metro route and station information
- Receive automated upcoming-station alerts
- Monitor their destination and journey status
- Manage a digital metro card
- Check card balance and recharge
- View transaction history
- Receive low-balance notifications
- Receive personalized journey completion messages

---

## 🚀 Core Features

### 🗺️ Journey & Route Management

- Metro route information
- Station information
- Journey planning
- Route assistance
- Boarding station management
- Destination station management
- Journey status assistance

### 🔔 Automated Journey Notifications

- Upcoming-station alerts
- Destination alerts
- Automated journey notifications
- Timely passenger assistance
- Personalized journey completion messages
- "Happy Journey" / travel notifications

### 💳 Digital Metro Card

- Digital metro card management
- Card balance tracking
- Recharge functionality
- Transaction history
- Low-balance notifications

### ⚙️ Application Management

- Structured backend architecture
- RESTful API communication
- Database-driven operations
- Modular application design
- Responsive and user-focused interface

---

## 🏗️ System Architecture

```text
                    ┌──────────────────────┐
                    │      React.js        │
                    │      Frontend        │
                    └──────────┬───────────┘
                               │
                               │ HTTP / REST
                               ▼
                    ┌──────────────────────┐
                    │      REST APIs       │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     Spring Boot      │
                    │   Business Logic     │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     SQL / Oracle     │
                    │       Database       │
                    └──────────────────────┘
