# eShopWay:- 

eShopWay is a comprehensive e-commerce platform built with the MERN stack, designed to facilitate seamless online shopping experiences for customers, sellers, and administrators. The platform includes user-friendly features like real-time notifications, live chat support, and secure payment processing.


## Table of Contents
1.Project Overview
2.Features
3.Tech Stack
4.Getting Started
5.Environment Variables



# Project Overview:-
eShopWay is a full-featured e-commerce application that allows customers to browse products, manage shopping carts, and complete secure payments. Sellers can manage their product listings, view customer orders, and track order status, while admins have control over the entire platform, including user management and order processing.

# Features:-
### Customer Features
1.Sign-up & Login: JWT-based authentication.
2.Product Catalog & Search: Browse and search for products.
3.Shopping Cart: Add, remove, and manage items in the cart.
4.Checkout & Payment: Secure payment integration with Stripe/PayPal.
5.Order Tracking: Track order status in real-time.
6.Live Chat Support: Chat with sellers and customer support using Socket.io.

-->Seller Features:-
1.Sign-up & Login: Separate access for sellers.
2.Product Management: Add, edit, and delete products.
3.Order Notifications: Receive real-time notifications on new orders and stock updates.
4.Chat with Customers: Real-time communication with customers.

-->Admin Features:-
1.Admin Dashboard: Manage users, sellers, and products.
2.Order Management: Oversee all orders and statuses.
3.Real-time Notifications: Alerts for order updates and stock changes.

-->>Tech Stack:-
1.Frontend: React, JavaScript, Tailwind CSS
2.Backend: Node.js, Express.js
3.Database: MongoDB
4.Authentication: JWT (JSON Web Tokens)
5.Real-time Communication: Socket.io
6.Payment Integration: Stripe/PayPal
7.Deployment: Vercel (frontend) and Render (backend)


-->Getting Started
To get a local copy of this project up and running, follow these steps:

-->>Prerequisites
Node.js and npm installed on your local machine.
MongoDB database (local or cloud-based).
Stripe/PayPal API keys for payment integration.
Installation
-->Clone the repository:
git clone git@github.com:abhiGithub302/e_shop_web_app.git


-->Navigate to the project directory:-
cd e_shop_web_app


-->Install dependencies for the backend:
cd backend
npm install

-->Install dependencies for the frontend:
cd ../frontend
npm install


-->Environment Variables
Create a .env file in the backend directory with the following variables:

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
EMAIL_HOST=your_email_host
EMAIL_PORT=your_email_port
EMAIL_USER=your_email_user
EMAIL_PASS=your_email_password
Usage
To start the development server:

-->Backend: Start the server from the backend directory:
npm run dev

-->Frontend: Start the frontend from the frontend directory:
npm start
