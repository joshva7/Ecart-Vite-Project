# ECart - React Vite E-Commerce Application

A modern frontend e-commerce application built with React and Vite. The project provides a responsive shopping experience with product browsing, cart management, user authentication, and protected routes using frontend-based state management.

---

## Project Overview

ECart is a frontend-focused e-commerce web application developed to demonstrate modern React development practices. The application includes user authentication, product listings, shopping cart functionality, and responsive user interfaces.

The project uses local data and frontend state management to simulate a real-world online shopping experience without requiring a backend server.

---

## Features

### Authentication & Authorization

* User Login
* User Registration
* Protected Routes
* Authentication State Management
* Session Persistence

### Product Management

* Product Listing
* Product Details View
* Category-Based Browsing
* Dynamic Product Rendering

### Shopping Cart

* Add to Cart
* Remove from Cart
* Update Quantity
* Cart Total Calculation

### User Experience

* Responsive Design
* Mobile-Friendly Layout
* Fast Performance with Vite
* Clean and Modern UI

---

## Tech Stack

### Frontend

* React.js
* Vite
* JavaScript (ES6+)
* HTML5
* CSS3

### State Management

* React Hooks
* Context API / Local State

### Authentication

* Frontend Authentication Logic
* Local Storage Session Management

---

## Project Structure

```bash
ECart-Vite-Project/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── data/
│   ├── assets/
│   ├── routes/
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
├── vite.config.js
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/joshva7/Ecart-Vite-Project.git
cd Ecart-Vite-Project
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

Application runs at:

```bash
http://localhost:5173
```

---

## Authentication Flow

1. User registers or logs in.
2. Authentication state is stored locally.
3. Protected routes become accessible after login.
4. Unauthorized users are redirected to the login page.

---

##Live Website
https://ecommercewebsites3.netlify.app/

## Core Functionalities

### User Login

Users can securely access protected sections of the application through frontend authentication.

### Product Catalog

Products are displayed dynamically from local data sources.

### Shopping Cart

Users can:

* Add products to cart
* Remove products from cart
* Modify quantities
* View total order amount

### Route Protection

Restricted pages are only accessible to authenticated users.

---

## Learning Objectives

This project demonstrates:

* React Component Architecture
* React Hooks
* React Router
* Authentication and Authorization Concepts
* Protected Routes
* State Management
* Responsive Web Design
* Vite Development Workflow

---

## Future Enhancements

* Backend API Integration
* Database Connectivity
* JWT Authentication
* Payment Gateway Integration
* Order Management
* Wishlist Feature
* Product Search and Filters
* User Profile Management

---

## Disclaimer

This project is developed for educational and portfolio purposes. Authentication and authorization are implemented on the frontend to demonstrate application flow and user access control concepts.

---

## Author

Pradeesh Kumar

GitHub: https://github.com/joshva7
