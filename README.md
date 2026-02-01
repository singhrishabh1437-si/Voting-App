🗳️ Voting App (MERN Stack)

A full-stack Voting Application built using the MERN stack (MongoDB, Express, React, Node.js) as part of the freeCodeCamp “Build a Voting App” project.
The application allows users to create, share, vote on, and manage polls, with real-time aggregated results displayed visually.

✨ Features

🔐 User Authentication & Authorization
Secure login and registration using JWT and bcrypt for password hashing 

README

📊 Create & Manage Polls
Authenticated users can create polls with any number of options, view their own polls, and delete them when no longer needed 

README

🌍 Public Voting Access
Both authenticated and unauthenticated users can view and vote on all public polls 

README

📈 Live Poll Results Visualization
Poll results are displayed in chart form to show aggregated voting data clearly and intuitively 

README

➕ Add New Options to Existing Polls
Users can extend polls by adding new voting options if they don’t like the existing ones 

README

🛠️ Tech Stack

Frontend

React

Chart libraries (for result visualization)

Backend

Node.js

Express.js

MongoDB

Mongoose

Authentication & Security

JSON Web Tokens (JWT)

bcrypt

Tooling

Yarn

Prettier (code formatting)

Shell script for concurrent startup

📂 Project Structure
vote-app/
├── client/        # React frontend
├── server/        # Express + MongoDB backend
├── .gitignore
├── .gitattributes
├── .prettierrc
├── .prettierignore
├── start.sh
└── README.md

▶️ Getting Started
1️⃣ Environment Setup

Create a .env file inside the server directory:

PORT=4000
DATABASE=mongodb://localhost/<DATABASE_NAME>
SECRET=ThisIsATemporarySecretKey


README

2️⃣ Install Dependencies
cd server && yarn install
cd ../client && yarn install

3️⃣ Run the Application
sh start.sh


This starts both the backend server and React frontend simultaneously 

start

🎯 Project Goals

This project was built to:

Practice full-stack MERN development

Implement secure authentication

Work with REST APIs and MongoDB

Build real-time interactive applications

Fulfill freeCodeCamp Voting App user stories

🚀 Future Improvements

User profiles and avatars

Poll expiration dates

Vote history tracking

Improved UI/UX with modern component libraries

Rate-limiting and anti-spam protection
