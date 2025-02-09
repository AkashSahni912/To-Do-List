TodoBuddy - Task Management Application
Overview
TodoBuddy is a task management web application that helps users to organize their daily tasks effectively. Users can register, log in, create tasks, and keep track of their productivity with ease. This app provides features such as logging in, signing up, and organizing tasks.

Features
User Authentication: Users can register, log in, and log out.
Task Management: Users can add, update, and delete tasks.
Toast Notifications: Success and error messages using Toastify.
Responsive Design: Designed to work seamlessly on both desktop and mobile devices.

Tech Stack
Frontend: React.js, React Router
State Management: Context API
CSS: Custom styling
Backend: Node.js, Express.js (Assumed based on your API usage)
Database: MongoDB (Assumed from user-based storage)

Features Implementation
Login/Signup Flow: User authentication is handled using API calls to register and log in. On successful login/signup, a toast notification is shown, and users are redirected to the homepage.
Protected Routes: Certain routes, like the homepage and task management page, are protected and can only be accessed by authenticated users.
Logout: Users can log out from the app, which clears their session and redirects them to the landing page.
Task Management: Users can create tasks, edit them, and mark them as completed or delete them.

Project Structure
├── public/
│   └── index.html         # Main HTML file
├── src/
│   ├── components/        # All React components
│   │   ├── Nav.js         # Navigation bar
│   │   ├── Logout.js      # Logout button component
│   │   ├── LoginForm.js   # Login form component
│   │   └── Register.js    # Signup form component
│   ├── context/           # React Context API for managing auth state
│   ├── App.js             # Main App component
│   └── index.js           # App entry point
└── .env                   # Environment variables


