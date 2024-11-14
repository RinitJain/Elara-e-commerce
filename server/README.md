# Elara E-commerce Website - Server (Node + Express)

This is the backend for the Elara E-commerce website, built with Node and Express, with MongoDB for the database.

## Prerequisites

- [Node.js](https://nodejs.org/) and npm
- MongoDB database (connection string required)

## Installation

1. **Navigate to the `server` folder:**
   ```bash
   cd server
```

2. **Install Dependencies:**
```bash
npm install
```

## Environment Setup
Create a .env file in the project root directory and add your MongoDB connection string along with any other required environment variables:

```makefile
MONGO_URL="your-mongo-connection-string"
PORT=5000
```

## Starting the Server
To start the server in development mode, run:

```bash
npm start
```

The server will be available at http://localhost:5000.

