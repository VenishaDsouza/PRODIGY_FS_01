# PRODIGY_FS_01
# Secure User Authentication System

A full-stack web authentication project built with Node.js, Express, MongoDB, and JWT. It features secure session handling using cookies, dynamic frontend rendering, and toast-based user feedback for clean UX.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Password Security**: bcrypt
- **Session Management**: Cookies with `httpOnly`, `sameSite`, `secure`
- **Feedback UX**: Toast notifications

---

## Features

- User registration and login
- JWT-based authentication stored in browser cookies
- Protected dashboard with user data fetched from `/profile`
- Secure logout clears token cookie
- Responsive toast messages after key actions
- Graceful error handling and form validation

---

## Setup Instructions

### 1. Clone this repository  
```bash
git clone https://github.com/VenishaDsouza/PRODIGY_FS_01

### 2. Install Backend Dependencies
cd server
npm install

### 3. Set up Environmental Variables
- Create a .env file inside server/ with:
MONGODB_URI=your-mongo-db-url
JWT_SECRET=your-secret-key

### 4. Run Your Backend Server 
npm start


