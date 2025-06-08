# 📦 BackAdmin – Inventory Management Backend API

**BackAdmin** is a RESTful API built with **Node.js**, **Express**, and **TypeScript**, designed for managing products, categories, suppliers, users, and inventory operations such as product registration and product output.  
It is ideal for small to medium-sized business inventory systems, supporting authentication, validation, and secure access control using JWT.

---

## 🚀 Features

- ✅ User authentication with JWT and bcrypt
- 📦 Product management (CRUD)
- 🧾 Category and supplier registration
- 📥 Product stock registration (entrada)
- 📤 Product output tracking (salida)
- 🔒 Protected routes with role-based token validation
- 📚 Organized by MVC structure + Sequelize ORM

---

## 🧠 Tech Stack

| Technology   | Purpose                           |
|--------------|-----------------------------------|
| Node.js      | Backend runtime                   |
| Express      | Routing and server logic          |
| TypeScript   | Static typing                     |
| Sequelize    | ORM for MySQL                     |
| MySQL        | Relational database               |
| bcrypt       | Password hashing                  |
| JWT          | Secure token-based authentication |
| dotenv       | Environment configuration         |
| CORS         | Cross-Origin Resource Sharing     |

---

## 📂 Project Structure

backadmin/
├── src/
│ ├── controllers/ # All business logic per entity
│ ├── models/ # Sequelize models and associations
│ ├── routes/ # Express routes with validation middleware
│ ├── db/ # Sequelize DB connection
│ ├── error/ # Centralized error messages
│ ├── index.ts # App entry point
│ └── models/server.ts # Express + middleware setup
├── dist/ # Compiled JS output
├── tsconfig.json # TypeScript config
├── .env # (not included) Environment variables
└── package.json



---

## ⚙️ Environment Variables

Create a `.env` file in the root directory with the following:

```env
PORT=3001
SECRET_KEY=your_jwt_secret_key


git clone https://github.com/ANavas07/Inventory-system-backend.git
cd Inventory-system-backend


npm install

npm run typescript     # In one terminal
npm run dev            # In another terminal

