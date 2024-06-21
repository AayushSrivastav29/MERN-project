# Blog App - MERN Stack Project

Welcome to the Blog App, a full-stack blogging platform built using the MERN stack (MongoDB, Express, React, Node.js). This project demonstrates CRUD operations, user authentication with JWT tokens, and a clean, responsive UI.


## Features

- User authentication with JWT (JSON Web Tokens)
- Create, Read, Update, and Delete (CRUD) operations for blog posts
- Responsive design
- Login and Signup pages
- Secure password hashing
- User profile management

## Installation

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running

### Backend Setup (API)

1. Clone the repository:

    ```bash
    git clone https://github.com/AayushSrivastav29/MERN-project.git
    cd blog-app/api
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `api` folder and add the following environment variables:

    ```plaintext
    PORT=5000
    MONGODB_URI
    JWT_SECRET
    ```

4. Start the backend server:

    ```bash
    npm start
    ```

### Frontend Setup (Client)

1. Navigate to the `client` folder:

    ```bash
    cd ../client
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `client` folder and add the following environment variable:

    ```plaintext
    REACT_APP_API_URL=http://localhost:3000
    ```

4. Start the frontend development server:

    ```bash
    npm start
    ```

## Usage

1. Open your browser and navigate to `http://localhost:3000` to view the application.
2. Sign up for a new account or log in with existing credentials.
3. Create, Read, edit, or delete blog posts.


