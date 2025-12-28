
# MERN Stack Application

This repository contains **MY WORK** of full-stack web application building using the MERN stack. The project follows a decoupled architecture, separating the client-side interface from the server-side logic to ensure scalability and maintainability.

## Table of Contents

* Project Overview
* Technologies Used
* Features
* Architecture
* Installation and Setup
* Environment Variables
* License

---

## Project Overview

This application serves as a comprehensive example of a modern full-stack application. It leverages a non-relational database for flexible data storage, a robust backend framework for API development, and a component-based frontend library for a dynamic user experience.

## Technologies Used

| Layer | Technology |
| --- | --- |
| **Database** | MongoDB (NoSQL) |
| **Backend Framework** | Express.js |
| **Frontend Library** | React.js |
| **Runtime Environment** | Node.js |
| **State Management** | Redux Toolkit (or React Context API) |
| **Styling** | CSS Modules / Tailwind CSS |

## Features

* **User Authentication:** Secure signup and login functionality using JSON Web Tokens (JWT) and Bcrypt for password hashing.
* **RESTful API:** A structured API following standard HTTP methods (GET, POST, PUT, DELETE).
* **State Management:** Efficient global state handling for seamless data flow across components.
* **Responsive Design:** Optimized for various screen sizes, including mobile, tablet, and desktop.
* **CRUD Operations:** Full Create, Read, Update, and Delete capabilities for the application's primary data models.

---

## Architecture

The application is split into two main directories:

1. **Client:** The React-based frontend.
2. **Server:** The Node.js and Express-based backend.

---

## Installation and Setup

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mern-stack.git
cd mern-stack

```

### 2. Backend Setup

Navigate to the server directory and install dependencies:

```bash
cd server
npm install

```

### 3. Frontend Setup

Navigate to the client directory and install dependencies:

```bash
cd ../client
npm install

```

### 4. Run the Application

You can run the client and server separately, or use a tool like **Concurrently** if configured:

**Start Server:**

```bash
# inside /server
npm start

```

**Start Client:**

```bash
# inside /client
npm start

```

---

## Environment Variables

To run this project, you will need to add the following environment variables to a `.env` file in your **server** directory:

* `PORT`: The port number for the server (e.g., 5000).
* `MONGODB_URI`: Your MongoDB connection string.
* `JWT_SECRET`: A secure string for token signing.

---

<div align="right">
<img width="300" alt="my_signature-png" src="https://github.com/user-attachments/assets/5012b07e-0892-4704-bf64-af2ef7ff0660" />
</div>



