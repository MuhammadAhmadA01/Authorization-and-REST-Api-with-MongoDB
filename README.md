# Authorization using JWT and REST API with MongoDB

This project demonstrates how to implement user authentication and authorization using JSON Web Tokens (JWT) and a RESTful API with MongoDB as the database.

## About

User authentication and authorization are essential components of many web applications. This project provides a boilerplate setup for implementing these features using JWT for token-based authentication and authorization, along with a RESTful API built with Node.js and Express.js, and MongoDB as the database.

## Features

- **User Registration:** Allows users to register by providing basic information such as username, email, and password.
- **User Authentication:** Handles user login and generates JWT tokens for authenticated users.
- **Authorization Middleware:** Protects routes by validating JWT tokens and ensuring authorized access.
- **Password Hashing:** Utilizes bcrypt for secure password hashing and storage in the database.
- **MongoDB Integration:** Uses MongoDB as the database for storing user information and authentication tokens.
- **Error Handling:** Includes error handling middleware to handle various types of errors and provide appropriate responses.

## Technologies Used

- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT), bcrypt
- **Deployment:** Heroku

## Getting Started

To get started with Authorization using JWT and REST API with MongoDB locally, follow these steps:

1. Clone this repository: `git clone https://github.com/MuhammadAhmadA01/Authorization-using-jwt-and-REST-Api-with-MongoDB.git`
2. Navigate to the project directory: `cd Authorization-using-jwt-and-REST-Api-with-MongoDB`
3. Install dependencies: `npm install`
4. Set up environment variables: Create a `.env` file in the root directory and define the following variables:
    ```
    PORT=3000
    MONGODB_URI=<your_mongodb_uri>
    JWT_SECRET=<your_jwt_secret>
    ```
5. Start the development server: `npm start`

Make sure you have Node.js and npm installed on your machine, and MongoDB installed and running locally or replace `<your_mongodb_uri>` with your MongoDB connection URI.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
