<img width="1850" height="871" alt="Screenshot 2026-11-03 120959" src="https://github.com/user-attachments/assets/c8ca60a0-4da6-4594-b3f8-ce82510be960" /># 👟 SneakPeak — Sneaker E-Commerce Website

A full-stack sneaker e-commerce web application developed as part of a MERN Stack training program.

SneakPeak is designed to provide users with a convenient online sneaker-shopping experience. Users can explore sneakers, manage their wishlists and shopping carts, and view their orders. The application also includes a dedicated admin dashboard for managing products, orders, inventory, and customers.

## 🌐 Live Demo

- **Frontend:** https://sneakpeak11.vercel.app/
- **Backend:** https://sneakpeak-api-cphr.onrender.com/

## 📸 Project Preview

<img width="1830" height="868" alt="Screenshot 2026-11-03 120440" src="https://github.com/user-attachments/assets/bb60e270-05e9-4101-92c0-68645f576548" />
<img width="1831" height="875" alt="Screenshot 2026-11-03 120457" src="https://github.com/user-attachments/assets/6115759b-61e5-4576-8149-7715e41d3b85" />
<img width="1868" height="878" alt="Screenshot 2026-11-03 120521" src="https://github.com/user-attachments/assets/2d2087a1-bceb-4e52-a83e-a15a82dc4b8f" />
<img width="1853" height="877" alt="Screenshot 2026-11-03 120556" src="https://github.com/user-attachments/assets/754967d3-f08f-41f2-8f7b-6b45a51687b6" />
<img width="1832" height="885" alt="Screenshot 2026-11-03 120703" src="https://github.com/user-attachments/assets/5de5ff66-85a8-48ce-93e7-143be28e5d79" />
<img width="1812" height="891" alt="Screenshot 2026-11-03 120609" src="https://github.com/user-attachments/assets/326274f3-a9bb-40b4-ace7-9292da8c3dcb" />
<img width="1821" height="893" alt="Screenshot 2026-11-03 120728" src="https://github.com/user-attachments/assets/2399f838-a636-42ca-91df-1c079dfc7a33" />
<img width="1805" height="842" alt="Screenshot 2026-11-03 120647" src="https://github.com/user-attachments/assets/9b95405c-839f-45fe-92df-3d9ce9a09e83" />
<img width="1866" height="877" alt="Screenshot 2026-11-03 120908" src="https://github.com/user-attachments/assets/b689a537-2e4a-4ee2-8f9d-ad9fabd1f8a2" />
<img width="1860" height="877" alt="Screenshot 2026-11-03 120927" src="https://github.com/user-attachments/assets/75f77ada-38d1-4225-913a-57c461292860" />
<img width="1867" height="892" alt="Screenshot 2026-11-03 120942" src="https://github.com/user-attachments/assets/9c489010-d52f-49c8-b9d7-e8c60b7d8cac" />
<img width="1850" height="871" alt="Screenshot 2026-11-03 120959" src="https://github.com/user-attachments/assets/7f4fc2e7-415f-4065-844a-74759e61a800" />
<img width="1857" height="872" alt="Screenshot 2026-11-03 121013" src="https://github.com/user-attachments/assets/43bd809a-3cec-4d33-8f42-034ab77df293" />

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
