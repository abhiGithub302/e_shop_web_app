# eShopWay

eShopWay is a full-featured e-commerce platform built using the MERN stack, aimed at delivering a seamless online shopping experience for customers, sellers, and administrators. This application includes real-time notifications, live chat support, and secure payment processing.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

eShopWay is a robust e-commerce application that lets customers browse products, manage their shopping cart, and complete secure payments. Sellers can manage their product listings, view customer orders, and track order statuses, while admins have full control over the platform, including user management and order processing.

## Features

### Customer Features

- **Sign-up & Login:** JWT-based authentication.
- **Product Catalog & Search:** Browse and search for products.
- **Shopping Cart:** Add, remove, and manage items in the cart.
- **Checkout & Payment:** Secure payment integration with Stripe/PayPal.
- **Order Tracking:** Real-time order status tracking.
- **Live Chat Support:** Chat with sellers and customer support via Socket.io.

### Seller Features

- **Sign-up & Login:** Separate access for sellers.
- **Product Management:** Add, edit, and delete products.
- **Order Notifications:** Receive real-time notifications for new orders and stock updates.
- **Customer Chat:** Real-time chat with customers.

### Admin Features

- **Admin Dashboard:** Manage users, sellers, and products.
- **Order Management:** Oversee all orders and statuses.
- **Real-time Notifications:** Alerts for order updates and stock changes.

## Tech Stack

- **Frontend:** React, JavaScript, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Real-time Communication:** Socket.io
- **Payment Integration:** Stripe/PayPal
- **Deployment:** Vercel (frontend) and Render (backend)

## Getting Started

To get a local copy of this project up and running, follow these steps:

### Prerequisites

- Node.js and npm installed on your local machine.
- MongoDB database (local or cloud-based).
- Stripe/PayPal API keys for payment integration.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abhiGithub302/e_shop_web_app.git

2. Navigate to the project directory:
   ```bash
   cd eShopWay

3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install

4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install

### Environment Variables
- PORT = 8000
- DB_URL = 
- JWT_SECRET_KEY = 
- JWT_EXPIRES = 7d
- ACTIVATION_SECRET = 
- SMPT_SERVICE = gmail
- SMPT_HOST = smtp.gmail.com
- SMPT_PORT = 465 
- SMPT_PASSWORD = 
- SMPT_MAIL = 
- STRIPE_API_KEY = 
- STRIPE_SECRET_KEY = 

### Usage
To start the development server:
 1. Backend: Start the server from the backend directory:
 - npm run dev
 2. Frontend: Start the frontend from the frontend directory:
 - npm start








   
