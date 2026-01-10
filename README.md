# Deathman - A MERN Stack Hangman Game

Welcome to **Deathman**, a modern twist on the classic Hangman game built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). Sign up, log in, and compete on the global leaderboard to see how you stack up against players around the world!

**Live Site:** [https://deathman.vercel.app/](https://deathman.vercel.app/)

## Features

- Classic Hangman gameplay
- User authentication (signup, login, logout)
- Forgot password functionality (via email with Nodemailer)
- Global leaderboard
- Toast notifications and clean UI/UX
- Fully responsive design

## Built With

- **MongoDB** – Database for user accounts and scores  
- **Express.js** – Backend framework for APIs  
- **React.js** – Frontend library for UI  
- **Node.js** – Backend runtime environment  

## Getting Started Locally

1. **Clone the repository**
  ```bash
  git clone https://github.com/yaoamegandjin/deathman.git
  ```
2. **Install dependencies**
  ```bash
  cd server
  npm install
  npm install nodemailer
  cd ../client
  npm install
  npm install use-sound
  npm install --save react-toastify 
  npm install axios 
  ```
3. **Set up environment variables**
Create a .env file in the /server directory with the following keys:
  ```env
  MONGO_URL=your_mongodb_connection_string
  PORT=8000
  SECRET_KEY=your_jwt_secret_key
  RESET_PASSWORD_KEY=your_password_reset_key
  GOOGLE_EMAIL=your_email@gmail.com
  GOOGLE_EMAIL_APPS_PW=your_gmail_app_password
  ```
4. **Run the app**
  ```bash
  # Start server
  cd server
  npm start

  # start client
  cd ../client
  npm start
  ```