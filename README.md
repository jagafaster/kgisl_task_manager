# Task Manager App (MERN)

## Overview
Task Manager App is a simple MERN stack web application to manage daily tasks.  
It allows users to perform full CRUD operations:
- Add a task
- View all tasks
- Update a task
- Delete a task

No authentication is included as per the task requirement. The focus is purely on core functionality.

---

## Tech Stack
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- API Testing: Postman (optional)

---

## Features
### Backend (Node.js, Express, MongoDB)
- Task Schema with:
  - title
  - dueDate
  - priority (Low, Medium, High)
  - status (Pending, In Progress, Completed)
  - createdAt (default date)

### API Endpoints
- POST /api/tasks → Add a new task
- GET /api/tasks → Get all tasks
- PUT /api/tasks/:id → Update a task
- DELETE /api/tasks/:id → Delete a task

---

## Backend Setup (Run Instructions)
### Step 1: Navigate to backend folder
cd backend

### Step 2: Install dependencies
npm install

### Step 3: Create .env file inside backend folder
Add your MongoDB connection string:
MONGO_URI=your_mongodb_connection_string
PORT=5000

### Step 4: Start the backend server
Backend will run on: http://localhost:5000


---

## Frontend Setup (Run Instructions)
### Step 1: Navigate to frontend folder
cd frontend

### Step 2: Install dependencies
npm install

### Step 3: Start the React app
npm start

Frontend will run on: http://localhost:3000

---

## How to Use the Application
1. Open the frontend in browser (localhost:3000)
2. Add a task with title, due date, priority, and status
3. View all tasks in the task list
4. Click Edit to update a task
5. Click Delete to remove a task from database

---

## Important Notes
- Ensure MongoDB is running locally OR use MongoDB Atlas.
- .env file is used for secure database connection.
- package.json is included in both frontend and backend folders.
- Application runs without errors as per assignment requirements.
- Styling is minimal since functionality is the main focus.

---

## Submission Checklist (Completed)
✔ Add Task  
✔ View Task List  
✔ Update Task  
✔ Delete Task  
✔ MERN Stack Used  
✔ .env for MongoDB Connection  
✔ Separate frontend & backend folders  
