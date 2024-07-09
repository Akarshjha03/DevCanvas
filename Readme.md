# MERN Full Stack Application

This repository contains a comprehensive web application built using the MERN stack (MongoDB, Express.js, React, Node.js). The project features user authentication, RESTful APIs, responsive design, and state management with Redux.

## Technology Used


## Features

- **MongoDB**: Database for storing user data and other information.
- **Express.js**: Web framework for building the backend API.
- **React**: Frontend library for building the user interface.
- **Node.js**: JavaScript runtime for running the backend server.
- **Redux**: State management for maintaining the application state.
- **User Authentication**: Secure login and registration system.
- **Responsive Design**: Mobile-first design to ensure compatibility with all devices.
- **RESTful APIs**: Structured API for interaction between frontend and backend.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/mern-fullstack-app.git
    cd mern-fullstack-app
    ```

2. Install dependencies for both frontend and backend:
    ```sh
    cd backend
    npm install
    cd ../frontend
    npm install
    ```

3. Create a `.env` file in the backend directory and add your environment variables:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. Start the development servers:
    - Backend:
        ```sh
        cd backend
        npm run dev
        ```
    - Frontend:
        ```sh
        cd frontend
        npm start
        ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Register a new user or log in with existing credentials.
3. Explore the features of the application.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

