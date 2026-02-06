## 👩‍💻 Key Learnings

[🇧🇷 Leia esta documentação em Português](./README.pt-BR.md)

During the development of "Support Tickets," I explored and applied several fundamental concepts for backend web projects, focusing on building a server from scratch. Key takeaways include:

Low-Level HTTP Server:

--> Protocol Fundamentals: Practical understanding of how the native http module handles sockets and streams, including manual processing of requests (req) and responses (res).

--> Custom Routing: Implementation of a manual router that processes HTTP methods and URLs (req.url), mapping them directly to controller functions.

Middleware Architecture:

--> Pipeline Construction: Building a middleware chain to process requests before they reach the controller. This includes a manual Body Parser implementation to handle JSON payloads for POST and PUT requests.

--> Separation of Concerns: Using middlewares to isolate crucial responsibilities, such as error handling and initial data validation.

Modularization & Code Organization:

--> ES6 Modules: Dividing code into logical files (controllers, services, etc.) using import/export syntax, ensuring the project remains scalable and navigable.

--> RESTful Patterns: Reinforcing the mapping of HTTP verbs (GET, POST, PUT, PATCH, DELETE) to resource management operations.

Essential Native Modules:

--> File System (fs): Utilizing the fs module for asynchronous data persistence and logging.

--> Crypto & IDs: Leveraging the crypto module to generate unique identifiers (UUIDs), a security best practice for data management.

## 💻 Project Structure
SUPPORT-TICKETS-PROJECT 

├── node_modules/ # Dependencies (Git ignored) 

├── src/ # Backend source code 

├── .gitignore 

├── Insomnia_Collection_Tickets.json.yaml 

├── README.md 

├── README.pt-BR.md 

└── package-lock.json

## 💾 Prerequisites

--> Node.js (version [v22.17.0])

--> npm or yarn (Package manager)

--> Insomnia or Postman (For API testing)

## 🚀 Getting Started

This API uses Vanilla Node.js (no frameworks) and a JSON file (db.json) for simulated data persistence.

--> Installation: Clone the repository and install the dependencies.

--> Run the Server: Start the backend development server: npm run dev

--> Usage: Use Insomnia or Postman to test the API endpoints (GET, POST, PUT, DELETE, PATCH).

## 🛠️ API Testing with Insomnia

--> Locate the collection file: Insomnia_Collection_Tickets.json.

--> Import it into Insomnia.

All requests are pre-configured to the default URL: http://localhost:[YOUR_PORT].

## ⚙️ Technologies

This project was built using:

--> Node.js (Native Modules)

--> JavaScript (ES6+)

--> Git & GitHub
