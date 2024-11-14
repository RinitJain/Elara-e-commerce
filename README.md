# Elara E-commerce Website

The **Elara E-commerce** website is a full-stack application built using the **MERN stack**. It features a React-based frontend, a Node/Express backend, and a MongoDB database.

## Project Structure

```plaintext
Elara-website/
├── client/    # Frontend (React + Vite)
├── server/    # Backend (Node + Express)
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm
- MongoDB database (connection string to be configured in the `.env` file)

### Installation

1. **Clone the Repository**
    ```bash
    git clone (https://github.com/RinitJain/Elara-e-commerce.git)
    cd Elara-website
    ```

2. **Install Client (Frontend)**
    ```bash
    cd client
    npm install
    ```

3. **Install Server (Backend)**
    ```bash
    cd ../server
    npm install
    ```

### Environment Setup

In the `server` folder, create a `.env` file and add your MongoDB URI and any other environment variables:

```dotenv
MONGO_URL="your-mongo-connection-string"
PORT=5000
```

### Running the Project
1. **Start the Backend:**

```bash
cd server
npm run dev
```
2. **Start the Frontend:** In a separate terminal window, run:

```bash
cd client
npm run dev
```
Visit the following URLs:

Frontend: http://localhost:5173
Backend: http://localhost:5000

