
---

# GoMicroServ-Study

**Implementing Microservices with Go and Docker**

This repository serves as a study and implementation guide for building microservices using the Go programming language and Docker. It encompasses various services that collectively demonstrate the microservices architecture, inter-service communication, and deployment strategies.

---

##  Project Structure

The project is organized into several services, each residing in its own directory:

* `authentication-service/` – Handles user authentication and authorization.
* `broker-service/` – Acts as an API gateway, routing requests to appropriate services.
* `front-end/` – Provides the user interface for interacting with the system.
* `listener-service/` – Listens for events and processes them accordingly.
* `logger-service/` – Manages logging across different services.
* `mail-service/` – Responsible for sending emails and notifications.
* `project/` – Contains shared configurations and utilities.
* `.gitattributes` – Git configuration for handling repository attributes.
* `.DS_Store` – macOS system file (can be ignored or removed).
* `workspace.code-workspace` – VS Code workspace configuration file.([Hostinger][1])

---

##  Getting Started

### Prerequisites

* [Go](https://golang.org/dl/) installed on your machine.
* [Docker](https://www.docker.com/get-started) installed and running.
* [Docker Compose](https://docs.docker.com/compose/install/) for orchestrating multi-container Docker applications.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Raygama/GoMicroServ-Study.git
   cd GoMicroServ-Study
   ```



2. **Build and run the services using Docker Compose:**

   ```bash
   docker-compose up --build
   ```



This command will build the Docker images for each service and start the containers.

---

## 🛠️ Usage

Once all services are up and running:([GitHub Docs][2])

* Access the front-end application by navigating to `http://localhost:PORT` in your web browser. Replace `PORT` with the actual port number configured for the front-end service.
* Use the application to interact with different services such as authentication, logging, and mailing.

---

##  Directory Overview

Here's a brief overview of each service:

* **authentication-service**: Manages user login, registration, and token generation.
* **broker-service**: Serves as the central point for routing requests to appropriate microservices.
* **front-end**: User interface built to interact with the backend services.
* **listener-service**: Monitors events and triggers corresponding actions.
* **logger-service**: Collects and stores logs from various services for monitoring and debugging.
* **mail-service**: Handles email dispatching for notifications and alerts.
* **project**: Contains shared resources and configurations used across services.

---

## Technologies Used

* **Go**: Primary language for developing microservices.
* **Docker**: Containerization of services for consistent deployment.
* **Docker Compose**: Tool for defining and running multi-container Docker applications.

---
