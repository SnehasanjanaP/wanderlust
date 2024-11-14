# Wanderlust

Wanderlust is a travel and adventure listing platform built using the MERN stack (MongoDB, Express.js, React, Node.js). Users can register, browse various travel listings, leave reviews. The project incorporates authentication, authorization, flash messages, and error handling for a smooth user experience.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Features
- **User Authentication**: Registration and login functionality using Passport.js.
- **Flash Messages**: Flash messaging for success and error notifications.
- **Travel Listings**: Users can view and create listings with descriptions and images.
- **Reviews**: Users can leave reviews on listings.
- **Error Handling**: Custom error handling and 404 page setup.

## Installation (Windows)

1. **Clone the repository**:
   Open Command Prompt or PowerShell, navigate to the desired directory, and run:
   powershell
   git clone https://github.com/yourusername/wanderlust.git
   cd wanderlust
   
2. **Install server dependencies**:
npm install

3. **Install client dependencies**:
cd client
npm install
cd ..

4. **Setup MongoDB**:
Make sure MongoDB is installed and running on your machine. 
By default, the app connects to mongodb://127.0.0.1:27017/wanderlust. If your MongoDB setup is different, update the MONGO_URL variable in the code.

5. **Setup Environment Variables**:
Create a .env file in the root directory with the following variables:
SECRET=your_secret_key_here
This project uses the following environment variables:
SECRET: Secret key used for session management and secure cookies.

6. **Run the Application**:
In Command Prompt or PowerShell, navigate to the project’s root folder, and run:
npm start

7. **Access the Application**:
Open your browser and go to http://localhost:8080.

##  Usage
Once the server is running, you can:
Register a new account or log in with an existing one.
View, add, edit, and delete travel listings.
Leave reviews on listings.
Use flash messages to see success and error notifications.

## Technologies Used
Backend: Node.js, Express.js, Passport.js (for authentication), Mongoose (for MongoDB integration)
Frontend: EJS templates for rendering views
Database: MongoDB for storing user data, listings, and reviews
Other: Dotenv for environment variables, Method-override for supporting HTTP verbs (PUT, DELETE)






