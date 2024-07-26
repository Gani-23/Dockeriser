# Containerized Cosmos
# Overview

This project demonstrates how to Dockerize a full-stack MERN application, consisting of a MongoDB database, Express.js server, React.js frontend, and Node.js backend. The goal is to containerize each component of the application and ensure that it can be easily deployed, scaled, and managed.

## Components

1. MongoDB Database
    - Container Name: mongodb
    - Image: mongo:4.4.14
    - Port: 27017

2. Express.js Server
    - Container Name: express-server
    - Image: node:14-alpine
    - Port: 3000

3. React.js Frontend
    - Container Name: react-frontend
    - Image: node:14-alpine
    - Port: 3001

4. Node.js Backend
    - Container Name: node-backend
    - Image: node:14-alpine
    - Port: 4000

## Setup

1. Clone the Repository: Clone this repository to your local machine using `git clone https://github.com/your-username/dockerized-mern-app.git`.

2. Install Dependencies: Run `npm install` in the root directory to install all dependencies.

3. Build Docker Images: Run `docker-compose build` to build the Docker images for each component.

4. Start Docker Containers: Run `docker-compose up` to start the Docker containers for each component.

## Running the Application

1. Start the Application: Run `docker-compose up` to start the Docker containers and the application.

2. Access the Application: Open a web browser and navigate to `http://localhost:3000` to access the React.js frontend.

3. Interact with the Application: Use the application as you would normally, and the data will be persisted in the MongoDB database.

## Technologies Used

- Docker: For containerization.
- Docker Compose: For managing and orchestrating the containers.
- MERN Stack: MongoDB, Express.js, React.js, and Node.js.
- Node.js: For the backend.
- React.js: For the frontend.
- MongoDB: For the database.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvement, please create an issue or submit a pull request.

