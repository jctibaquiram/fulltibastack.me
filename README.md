# FullTiBaStack

A full-stack web application developed step by step as part of structured full-stack training, with a focus on backend fundamentals, real-time communication, persistence, containerization, and deployment.

## 🚀 Overview

FullTiBaStack started as a simple Node.js HTTP server and evolved through several development stages, incorporating additional backend concepts and deployment practices.

The project provided hands-on experience with server-side JavaScript, WebSocket communication, database logging, Docker containerization, Linux/WSL environments, Nginx, and cloud deployment.

## 🛠️ Technologies

### Backend & Programming

* JavaScript
* Node.js
* Express.js
* WebSockets

### Infrastructure & Deployment

* Docker
* Linux / WSL
* Nginx
* DigitalOcean

### Development Tools

* Git
* GitHub
* npm

## ✨ Features

* HTTP server built with Node.js and Express
* Real-time communication using WebSockets
* Client/server WebSocket implementation
* Database logging
* Docker-based application deployment
* Nginx reverse proxy configuration
* Linux-based server environment
* Git/GitHub version control workflow

## 📂 Project Structure

```text
fulltibastack.me/
├── app.js
├── index-ws.js
├── index.html
├── Dockerfile
├── github.sh
├── package.json
├── package-lock.json
└── README.md
```

## 🔄 Project Evolution

The project was developed incrementally while learning and applying new concepts:

1. **Initial HTTP server**

   * Created a basic Node.js server.
   * Implemented HTTP request handling.

2. **Real-time communication**

   * Added WebSocket server and client functionality.
   * Implemented communication between the application and connected clients.

3. **Database logging**

   * Added database-related logging functionality.
   * Extended the application to persist relevant information.

4. **Containerization and deployment**

   * Created a Docker-based deployment configuration.
   * Configured the application to run in a Linux environment.
   * Used Nginx as a reverse proxy.
   * Deployed the application to a DigitalOcean server.

## 🐳 Running Locally

### Prerequisites

Make sure you have installed:

* Node.js
* npm
* Docker (optional, for containerized execution)

### Install dependencies

```bash
npm install
```

### Run the application

```bash
node app.js
```

Depending on the project stage you want to explore, the WebSocket implementation can be started with:

```bash
node index-ws.js
```

## 🐳 Docker

The repository includes a `Dockerfile` for containerized execution.

Build the image:

```bash
docker build -t fulltibastack .
```

Run the container:

```bash
docker run -p 3000:3000 fulltibastack
```

## 🌐 Deployment

The application was deployed during development to a DigitalOcean Linux server.

The deployment environment included:

* Docker
* Nginx
* Linux
* Git/GitHub

The server is currently offline, so the project is provided as source code rather than as an active production deployment.

## 📚 What I Learned

This project helped me build practical experience with:

* Node.js server fundamentals
* Backend application structure
* HTTP communication
* WebSocket-based real-time communication
* Database logging
* Docker containerization
* Linux server environments
* Nginx reverse proxy configuration
* Git and GitHub workflows
* Application deployment and server administration

## 🎯 Purpose

This project represents an important step in my transition from an engineering and data-oriented background toward software engineering, with a growing focus on backend development and modern application infrastructure.

## 👤 Author

**Juan Camilo Tibaquira Montoya**

* LinkedIn: [linkedin.com/in/jctibaquiram](https://www.linkedin.com/in/jctibaquiram/)
* GitHub: [github.com/jctibaquiram](https://github.com/jctibaquiram)

---

⭐ This repository documents my hands-on learning process and progression through full-stack and backend development.
