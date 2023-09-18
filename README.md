# Go Gin MongoDB User CRUD

![Go](https://img.shields.io/badge/Go-v1.17-blue.svg)
![Gin](https://img.shields.io/badge/Gin-v1.7.4-green.svg)
![MongoDB](https://img.shields.io/badge/MongoDB-v4.4-yellow.svg)

Effortlessly manage user data with this robust Go (Golang) application built on the Gin web framework and MongoDB. Simplify user CRUD (Create, Read, Update, Delete) operations while ensuring performance, scalability, and security.

## Features
- **CRUD Operations:** Perform CRUD actions on user data.
- **MongoDB Integration:** Seamlessly connect to MongoDB for efficient data storage.
- **Middleware for Route Authorization:** Secure your routes with middleware for user authentication and authorization.
- **Robust Error Handling:** Gracefully handle errors for a smooth user experience.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone [repository URL]

2. **Locate to project Dir:**
   ```bash
    cd /project

3. **Install Dependencies:**
   ```bash
    go mod download

4. **Configure MongoDB:**
   * Install MongoDB and set up a database.
   * Update the MongoDB connection details in the configuration file.

5. **Run the Server:**
   ```bash
     go run main.go
