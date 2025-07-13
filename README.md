# MERN-Authentication

A full-stack authentication system built with the MERN stack (MongoDB, Express.js, React, Node.js). This project demonstrates secure user authentication, email verification, password reset, and protected routes using JWTs.

## Features
- User registration and login
- Email verification
- Password reset via email
- JWT-based authentication
- Protected routes
- Responsive UI with React and Tailwind CSS

## Technologies Used
- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Email:** Nodemailer, Brevo SMTP

## Getting Started

### Prerequisites
- Node.js & npm
- MongoDB Atlas account

### Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/<your-username>/MERN-Authentication.git
   cd MERN-Authentication
   ```
2. **Install server dependencies:**
   ```sh
   cd server
   npm install
   ```
3. **Install client dependencies:**
   ```sh
   cd ../client
   npm install
   ```

### Environment Variables
Create a `.env` file in the `server` directory with the following:
```
MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
NODE_ENV=development
SMTP_USER=<your-smtp-user>
SMTP_PASS=<your-smtp-pass>
SENDERS_EMAIL=<your-email>
```

### Running the App
1. **Start the backend server:**
   ```sh
   cd server
   npm start
   ```
2. **Start the frontend app:**
   ```sh
   cd ../client
   npm run dev
   ```

## Folder Structure
```
mern-auth/
├── client/        # React frontend
└── server/        # Express backend
```

## API Endpoints
- `/api/auth/register` - Register new user
- `/api/auth/login` - Login user
- `/api/auth/verify-email` - Verify email
- `/api/auth/reset-password` - Reset password

## License
This project is licensed under the MIT License.
