A full-stack web application designed to streamline task management, allowing users to register, log in, and perform CRUD operations (Create, Read, Update, Delete) on tasks. The application is built with a robust backend, responsive frontend, and secure database integration.

## Features
User Authentication: Secure registration and login using JSON Web Tokens (JWT).
Task Management: Create, view, update, and delete tasks seamlessly.
Responsive Frontend: Intuitive and user-friendly design built with React.js.
Robust Backend: API endpoints developed using Node.js and Express.js.
Secure Database: Data stored securely in MongoDB with well-designed schemas.
Error Handling: Meaningful error messages and validations for smooth user experience.
Security: Password hashing and protection against common vulnerabilities.

## Technologies Used
Frontend: React.js, HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT
Hosting: [Add hosting platform, e.g., Vercel/Heroku]


## Dependencies

Following are the major dependencies of the project:

- axios
- react
- react-dom
- react-redux
- react-router-dom
- react-toastify
- redux
- redux-thunk
- bcrypt
- cors
- dotenv
- express
- jsonwebtoken
- mongoose

## Dev-dependencies

Following are the major dev-dependencies of the project:

- nodemon
- concurrently

## Prerequisites

- Node.js must be installed on the system.
- You should have a MongoDB database.
- You should have a code editor (preferred: VS Code)

## Installation and Setup

1. Install all the dependencies

   ```sh
   npm run install-all
   ```

2. Create a file named ".env" inside the backend folder. Add data from .env.example file and substitute your credentials there.

3. Start the application

   ```sh
   npm run dev
   ```

4. Go to http://localhost:3000

## Backend API

<pre>
- POST     /api/auth/signup
- POST     /api/auth/login
- GET      /api/tasks
- GET      /api/tasks/:taskId
- POST     /api/tasks
- PUT      /api/tasks/:taskId
- DELETE   /api/tasks/:taskId
- GET      /api/profile
</pre>

## Frontend pages

<pre>
- /                 Home Screen (Public home page for guests and private dashboard (tasks) for logged-in users)
- /signup           Signup page
- /login            Login page
- /tasks/add        Add new task
- /tasks/:taskId    Edit a task
</pre>

## npm scripts

At root:

- `npm run dev`: Starts both backend and frontend
- `npm run dev-server`: Starts only backend
- `npm run dev-client`: Starts only frontend
- `npm run install-all`: Installs all dependencies and dev-dependencies required at root, at frontend and at backend.

Inside frontend folder:

- `npm start`: Starts frontend in development mode
- `npm run build`: Builds the frontend for production to the build folder
- `npm test`: Launches the test runner in the interactive watch mode
- `npm run eject`: This will remove the single build dependency from the frontend.

Inside backend folder:

- `npm run dev`: Starts backend using nodemon.
- `npm start`: Starts backend without nodemon.

## Demo Video
[screen-capture.webm](https://github.com/user-attachments/assets/67b90c24-1d9e-4363-a4d0-e015a7139ee2)

