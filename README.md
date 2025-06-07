Project Management API - Backend

Features - 

User Authentication: Secure user registration and login using JSON Web Tokens (JWT).
Password Hashing: Passwords are securely hashed using bcrypt before being stored.
Protected Routes: Middleware to protect sensitive endpoints, ensuring only authenticated users can access them.



Tech Stack - 

Runtime Environment: Node.js
Framework: Express.js
Database: MongoDB with Mongoose ODM
Authentication: JSON Web Tokens (jsonwebtoken)
Password Hashing: bcrypt
Environment Variables: dotenv

# The port the server will run on
PORT=3000

# Your MongoDB connection string
MONGO_URL = mongodb+srv://pushpanjali:Pushpanjali123@internship.prinr2j.mongodb.net/

# A secret key for signing JWTs
ACCESS_TOKEN_SECRET=123456
REFRESH_TOKEN_SECRET=1234567890
ACCESS_TOKEN_EXPIRY=15m
REFRESH_TOKEN_EXPIRY=7d
