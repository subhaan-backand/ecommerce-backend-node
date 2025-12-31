# E-Commerce Backend API

A backend application built using Node.js, Express.js and MongoDB.
This project includes user authentication, product management, cart and order APIs.

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

## Features
- User Register & Login
- JWT based Authentication
- Product CRUD APIs
- Cart Management
- Order Management
- Admin functionalities

## Installation & Run

1. Clone the repository
```bash
git clone https://github.com/subhaan-backand/ecommerce-backend-node.git

## API Endpoints

### Auth
- POST /api/auth/register
- POST /api/auth/login

### Products
- GET /api/products
- POST /api/products (Admin)
- PUT /api/products/:id (Admin)
- DELETE /api/products/:id (Admin)

### Cart
- POST /api/cart/add
- GET /api/cart
- PUT /api/cart/update
- DELETE /api/cart/remove

### Orders
- POST /api/orders
- GET /api/orders/user
- GET /api/orders (Admin)

## Environment Variables

Create a `.env` file in the root directory and add:

PORT=4500
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

## Run Locally

npm install  
npm start


## Author
Subhaan Raza  
Backend Developer (Node.js)  
Open to Remote Opportunities



