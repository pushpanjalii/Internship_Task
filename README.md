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

Screenshots of working APIs - 
Register User Api - 
![Screenshot 2025-06-07 161527](https://github.com/user-attachments/assets/b966caa8-0d87-486b-9d05-6d55216e2162)

Login User Api - 
![Screenshot 2025-06-07 161738](https://github.com/user-attachments/assets/edf15a3c-d978-40b0-af84-d9efc20c9b79)

Logout User Api - 
![Screenshot 2025-06-07 161834](https://github.com/user-attachments/assets/9b07a7ec-99ee-4a54-91b5-097a86231c82)

Change-Password-Api - 
![Screenshot 2025-06-07 161950](https://github.com/user-attachments/assets/26853fa5-b27c-4ad9-a470-3dd3a4a7cd75)

Get-current-User Api -
![Screenshot 2025-06-07 162051](https://github.com/user-attachments/assets/5edc8d28-a9de-4e4a-abf5-6d55c1d18e2e)


