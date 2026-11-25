# 👟 SneakPeak — Sneaker E-Commerce Website

A full-stack sneaker e-commerce web application developed as part of a MERN Stack training program.

SneakPeak is designed to provide users with a convenient online sneaker-shopping experience. Users can explore sneakers, manage their wishlists and shopping carts, and view their orders. The application also includes a dedicated admin dashboard for managing products, orders, inventory, and customers.

## 🌐 Live Demo

- **Frontend:** https://sneakpeak11.vercel.app/
- **Backend:** https://sneakpeak-api-cphr.onrender.com/

## 📸 Project Preview

Add your actual website screenshots here.

Recommended screenshots:
- Homepage
- Registration and Login
- Sneaker Shop
- Wishlist
- Shopping Cart
- My Account
- My Orders
- Admin Dashboard
- Admin Orders
- Admin Products
- Admin Inventory
- Admin Customers

## ✨ Features

### 👤 Customer Features

- User Registration and Login
- Browse Sneaker Products
- Product Catalogue
- Wishlist Management
- Shopping Cart
- My Account
- My Orders

### 🛠️ Admin Features

- Admin Dashboard
- Order Management
- Product Management
- Inventory Management
- Customer Management

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, Vite, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JWT, bcryptjs |
| HTTP Client | Axios |
| UI Icons | Lucide React |
| Security | Helmet, Express Rate Limit |
| API Testing | Postman |
| Development Tools | VS Code, Git, GitHub |
| Deployment | Vercel, Render |

## 🏗️ Project Architecture

SneakPeak follows a client-server architecture.

             USER
               |
               v
       REACT.JS FRONTEND
          (CLIENT)
               |
               v
          REST APIs
               |
               v
      NODE.JS + EXPRESS
          (SERVER)
               |
               v
       MONGODB DATABASE
          (MONGOOSE)

The React frontend communicates with the Express backend through APIs. The backend processes requests and interacts with MongoDB to store and retrieve application data.

## 📂 Project Structure

SneakPeak/
│
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── server/
│   ├── server.js
│   ├── package.json
│   ├── ...
│
├── README.md
└── .gitignore

## ⚙️ Installation and Setup

Follow these steps to run SneakPeak locally.

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB
- Git

### 1. Clone the Repository

git clone https://github.com/yudii1107/SneakPeak.git
cd SneakPeak

### 2. Setup the Frontend

Open a terminal:

cd client
npm install

Create a `.env` file inside the `client` directory and configure the backend API URL using the environment variable name expected by the frontend code.

Start the frontend:

npm run dev

### 3. Setup the Backend

Open another terminal from the project root:

cd server
npm install

Create a `.env` file inside the `server` directory and configure your MongoDB connection and authentication settings.

Example configuration:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Use the exact environment variable names required by your backend source code. Never upload actual passwords, database credentials, or secret keys to GitHub.

### 4. Start the Backend

For normal execution:

npm start

For development mode:

npm run dev

The backend uses Node.js and Express.js to handle API requests.

## 🚀 Deployment

The application is deployed using:

- **Frontend Hosting:** Vercel
- **Backend Hosting:** Render
- **Database:** MongoDB

Live application: https://sneakpeak11.vercel.app/

## 👨‍💻 Project Background and Contribution

SneakPeak was originally assigned as a team-based task during my MERN Stack training program.

Although the project was planned as a collaborative team assignment, the other team members did not complete their assigned work. I therefore took responsibility for completing the application independently and bringing its major functionalities together.

My contribution included frontend development, backend functionality, database integration, API integration, and overall application development.

This experience helped me understand the importance of taking ownership, solving problems independently, and completing a project from development to deployment.

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Building frontend interfaces using React.js
- Developing backend APIs using Node.js and Express.js
- Working with MongoDB and Mongoose
- Implementing authentication using JWT and bcryptjs
- Integrating frontend and backend
- Managing application data
- Testing APIs using Postman
- Using Git and GitHub for version control
- Deploying a full-stack web application

## 🔮 Future Improvements

Possible improvements for future versions include:

- Online payment gateway integration
- Product reviews and ratings
- Advanced product search and filtering
- Enhanced order tracking
- Additional security and performance improvements

## 📄 License

This project was developed for educational and learning purposes.

---

**Developed as part of a MERN Stack training project.**

👟 **SneakPeak — Step Into Your Style!**
