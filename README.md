# AngularProject
# Tech Content Publishing Platform - DEG Module

This project is a full-stack web application developed using **Angular** for the frontend and **Express.js** for the backend. It is designed as a module for a **Degree Program (DEG)** to allow students or faculty to **publish, manage, and explore technology-related content**.

## 📚 Project Overview

The platform enables:
- Users to create and publish tech articles.
- Browsing and searching of content by category or tags.
- Role-based access for students and admins.
- Secure authentication and content moderation.

## 🧰 Tech Stack

### Frontend (Angular)
- Angular 19+
- TypeScript
- Angular Material (UI components)
- CSS

### Backend (Express)
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- CORS, dotenv








## 📂 Folder Structure

**<pre>
├── node_modules/
├── src/
│   ├── config/            # Configuration files (DB, env, etc.)
│   │   └── db.js
│   ├── controllers/       # Route logic / business logic
│   │   └── userController.js
│   ├── models/            # Mongoose or Sequelize models
│   │   └── userModel.js
│   ├── routes/            # Express route definitions
│   │   └── userRoutes.js
│   ├── middleware/        # Custom middleware (auth, error handlers)
│   │   └── authMiddleware.js
│   ├── utils/             # Utility/helper functions
│   │   └── generateToken.js
│   ├── app.js             # Express app setup
│   └── server.js          # Starts the server
├── .env                   # Environment variables
├── .gitignore
├── package.json
└── README.md
</pre>**






**📘 Module Objective (for DEG)**

* This project serves as a practical module in a software engineering or IT-related degree. The objective is to:

* Understand full-stack architecture.

* Apply Angular and Express in a real-world scenario.

* Practice content-driven development with security and scalability in mind.
  

**🛠 Future Improvements**

* Add user profile pages

* Implement markdown support

* Add comment and like system

* Deployment with Docker or cloud services
