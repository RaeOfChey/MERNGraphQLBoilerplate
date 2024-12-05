# MERN GraphQL Boilerplate

### Status: In Progress

![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Tools and Technologies](#tools-and-technologies)
6. [Dependencies and Installs](#dependencies-and-installs)
7. [License](#license)
8. [Contributing](#contributing)
9. [Tests](#tests)
10. [Questions](#questions)

## Description
This repository is a boilerplate for creating full-stack applications using the MERN stack (MongoDB, Express.js, React.js, and Node.js) with a GraphQL API. It includes pre-configured JWT authentication, a clean project structure, and ready-to-use configurations for deployment. Ideal for rapid prototyping and scalable app development.

## Features
- Pre-configured GraphQL server with Express.js and Apollo Server.
- React front-end with basic routing setup using React Router.
- JWT-based authentication flow for secure user sessions.
- MongoDB connection with Mongoose schema examples.
- Ready-to-deploy configurations for platforms like Render or Heroku.
- ESLint and Prettier setup for code consistency.

## Installation
To use the application, follow these steps:

- Step 1: Clone the repository.
- Step 2: Navigate to the project directory by typing `cd MERNGraphQLBoilerplate`.
- Step 3: Navigate to the root, client, and server directories to install respective dependencies by running `npm install`, `cd client && npm install`, `cd ../server && npm install`.
- Step 4: Create .env files in the server directory with the following variables:

    PORT=3001  
    MONGO_URI=your_mongodb_connection_string  
    JWT_SECRET=your_secret_key
- Step 5: Run the application by running `npm run develop`.

## Usage
- Front-End: Navigate to `http://localhost:3000` to view the React application.
- Back-End: Access the GraphQL playground at `http://localhost:3001/graphql`.

## Tools and Technologies
- Front-End: React, React Router, Apollo Client
- Back-End: Node.js, Express.js, Apollo Server, Mongoose
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)
- Development Tools: ESLint, Prettier

## Dependencies and Installs

**Root Level**
- `concurrently` (for managing client and server in development mode)
**Client**
- `react`
- `react-dom`
- `react-router-dom`
- `@apollo/client`
**Server**
- `express`
- `apollo-server-express`
- `graphql`
- `mongoose`
- `jsonwebtoken`

## License
This project is licensed under the MIT License, which allows you to freely use, modify, and distribute this software, provided proper attribution is given.

## Contributing
At this time, contributions are not being accepted for this repository. However, feel free to fork the repo for personal use or to customize it for your own projects.

## Tests
Currently, this project does not have any automated tests.

## Questions
If you have any questions about the repository, feel free to reach out by opening an issue or contacting me directly at cheyennaraelynn@gmail.com You can also find more of my work on GitHub at https://github.com/RaeOfChey.
