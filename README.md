# Password Manager Web App

This is a full-stack password manager and password generator web application built using React (frontend) and Express.js (backend). The app allows users to sign up, log in, generate secure passwords, and manage them with custom labels — all presented in a clean and modern dark-themed UI.

---

## Features

###  User Authentication
- Sign up and log in with email and password
- Authentication managed using React Context
- Routing handled using React Router

### Password Generator
- Choose password length (6 to 32 characters)
- Toggle inclusion of uppercase, lowercase, numbers, and symbols
- Real-time password strength meter (Very Weak to Very Strong)
- Copy generated password to clipboard
- Add custom labels before saving passwords

###  Password Manager
- View saved passwords with labels
- Password list displayed in a neatly styled card format
- Easy copy functionality for saved passwords

### UI/UX Design
- Modern dark-themed interface
- Custom color palette (no standard red, blue, green, etc.)
- Smooth animations and transitions
- Responsive layout with visually pleasing components

---

## Tech Stack

### Frontend
- React (JavaScript)
- React Router DOM
- Context API for state management
- Custom CSS for dark theme

### Backend
- Node.js
- Express.js

---

## Folder Structure

sample/
│
├── public/
│
├── src/
│ ├── components/
│ │ ├── Auth/
│ │ │ ├── Login.js
│ │ │ └── Signup.js
│ │ ├── Passwords/
│ │ │ ├── PasswordGenerator.js
│ │ │ └── SavedPasswords.js
│ │ └── Dashboard.js
│ │
│ ├── context/
│ │ └── AuthContext.js
│ │
│ ├── router/
│ │ └── AppRouter.js
│ │
│ ├── styles/
│ │ └── theme.css
│ │
│ └── App.js
│
├── server/
│ └── index.js
│
└── README.md


---
