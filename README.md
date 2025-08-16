Overview:

This project is a full-stack E-Commerce platform built using the MERN Stack (MongoDB, Express.js, React, Node.js).
It allows users to browse products, search, filter, and purchase items securely.

Features:

👤 User Authentication – Register, login, and manage accounts.

🛍️ Product Management – Browse, search, filter, and sort products.

🛒 Shopping Cart – Add/remove items and manage cart.

💳 Secure Payments – Integrated payment gateway (Stripe).

🔑 Admin Dashboard – Manage products, categories, and users.

🌐 Responsive UI – Optimized for desktop and mobile devices.

Tech Stack:

Frontend: React, HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT (JSON Web Token)
Payments: Stripe

Installation & Setup:

Clone the repository

git clone https://github.com/VarshaPulikanti/e-commerce_platform.git
cd e-commerce_platform


Install backend dependencies

cd backend
npm install


Install frontend dependencies

cd ../frontend
npm install


Setup environment variables (.env file):

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_KEY=your_payment_api_key


Run the backend server

npm run server


Run the frontend

npm run dev
