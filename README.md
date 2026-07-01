# 📝 Simple ToDo List

A full-stack task management application built with the **MERN Stack** (MongoDB, Express.js, React.js, and Node.js). The application provides a simple and intuitive interface for creating, managing, updating, and deleting daily tasks while demonstrating CRUD operations, RESTful API integration, and full-stack web development principles.

---

## 📖 Overview

The **Simple ToDo List** is a full-stack web application that helps users organize their daily activities efficiently. It features a React-based frontend that communicates with a Node.js and Express.js backend through REST APIs, with MongoDB serving as the database for persistent task storage.

This project was developed to strengthen my understanding of full-stack development, API integration, database management, and frontend-backend communication.

---

## ✨ Features

- Create new tasks
- View all existing tasks
- Mark tasks as completed
- Delete completed or unwanted tasks
- Real-time updates through RESTful APIs
- Responsive and clean user interface

---

## 🛠️ Technology Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Development Tools
- Visual Studio Code
- Git & GitHub
- Postman

---

## 📂 Project Structure

```text
Simple-ToDo-List
│
├── todo-backend
│   ├── models
│   ├── routes
│   ├── server.js
│   ├── package.json
│   └── ...
│
└── todo-frontend
    ├── public
    ├── src
    ├── package.json
    └── ...
```

---

## 🚀 Getting Started

### Prerequisites

Before running the project, ensure you have the following installed:

- Node.js
- MongoDB
- npm

---

### Installation

#### Clone the Repository

```bash
git clone https://github.com/AlvinAnto-M/Simple-ToDo-List.git
```

Navigate to the project directory:

```bash
cd Simple-ToDo-List
```

---

### Backend Setup

```bash
cd todo-backend
npm install
npm start
```

The backend server will start on:

```
http://localhost:5000
```

---

### Frontend Setup

Open another terminal:

```bash
cd todo-frontend
npm install
npm start
```

The frontend application will run on:

```
http://localhost:3000
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/todos` | Retrieve all tasks |
| POST | `/todos` | Create a new task |
| PUT | `/todos/:id` | Update task status |
| DELETE | `/todos/:id` | Delete a task |

---

## 📸 Application Preview

Add screenshots of your application here.

Example:

```
assets/
├── home-page.png
├── add-task.png
└── completed-task.png
```

---

## 🎯 Learning Outcomes

This project helped me gain practical experience in:

- Full-Stack Web Development
- REST API Development
- CRUD Operations
- MongoDB Database Integration
- React Component Architecture
- State Management
- Client-Server Communication
- Version Control using Git & GitHub

---

## 🚀 Future Enhancements

- User Authentication
- Task Categories
- Due Dates and Reminders
- Task Priority Levels
- Search and Filter Functionality
- Dark Mode
- Drag and Drop Task Management
- Responsive Mobile Design

---

## 👨‍💻 Author

**Alvin Anto**

- GitHub: https://github.com/AlvinAnto-M
- LinkedIn: *(Add your LinkedIn Profile)*

---

## 📜 License

This project is intended for educational purposes and portfolio demonstration.
