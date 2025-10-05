Library Management System

Project Overview

This is a full-stack Library Management System designed to manage books, members, and transactions. It supports both admin and member functionalities, allowing for efficient tracking of library assets and user activity.

Tech Stack

This project is built using the MERN stack (MongoDB, Express, React, Node.js).

Category	Technology	Description

Frontend	React (with Hooks/Context API)	A fast and responsive user interface for both admin and members.
Backend	Node.js & Express	RESTful API for handling requests and business logic.
Database	MongoDB (with Mongoose)	Flexible NoSQL database for storing user, book, and transaction data.



Features

Admin Dashboard: Manage books (add, update, delete), view all members, and oversee all transactions.

Member Dashboard: View available books, check borrow history, and track current borrowings.

Transaction Management: Handle book issue and return processes with due date tracking.

User Authentication/Authorization: Secure login for both admin and members.

Getting Started
To get a copy of this project up and running on your local machine, follow these steps.

Prerequisites
You will need the following installed:

Node.js (LTS version recommended)

MongoDB (A local instance or a cloud service like MongoDB Atlas)

Installation
Clone the repository:

Bash

git clone https://github.com/EKANSHKUMAR1870/Library-Management-System.git
cd Library-Management-System
Install dependencies for the backend:

Bash

cd backend
npm install
Install dependencies for the frontend:

Bash

cd ../frontend
npm install
Configuration
Create a file named .env in the root of your backend directory.

Add your database connection string and a secret key:

MONGO_URI=mongodb+srv://[YOUR_DB_USER]:[YOUR_DB_PASSWORD]@clustername.mongodb.net/librarydb
JWT_SECRET=[ANY_LONG_RANDOM_STRING]
Running the Project
Start the backend server (from the backend directory):

Bash

npm start  # or npm run dev, depending on your setup
The server will run on http://localhost:5000 (or the port you configured).

Start the frontend application (from the frontend directory):

Bash

npm start
The app will open in your browser, usually at http://localhost:3000.

Contact
Created by Ekansh - [ https://www.linkedin.com/in/ekansh-kumar-4a0138283/ ]
