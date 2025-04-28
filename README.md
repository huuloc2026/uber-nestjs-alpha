# Building Uber Services with NestJS Microservices

[![Awesome](https://fptsmartcloud.com/wp-content/uploads/2022/10/what-is-microservice-glossary-01.png)](https://github.com/huuloc2026/)

This project demonstrates the foundational steps for building an Uber-like service using a NestJS microservices architecture. It covers setting up the backend infrastructure, database integration, and inter-service communication.

## Project Overview

This project serves as a practical guide to building the backend for a ride-hailing application similar to Uber. It focuses on utilizing NestJS, a progressive Node.js framework, and a microservices architecture to create scalable and maintainable services. The initial stages involve setting up the database (MongoDB), defining data models, handling data persistence, and establishing communication between different microservices using TCP.

## Key Features

* **NestJS Microservices:** Demonstrates the implementation of a microservices architecture using NestJS.
* **MongoDB Integration:** Shows how to connect and interact with a MongoDB database using NestJS Mongoose.
* **Dockerization:** Provides Docker and Docker Compose configurations for easy setup and management of database services.
* **Data Modeling:** Defines a schema for storing geographical coordinates.
* **Request Validation:** Implements validation for incoming request bodies.
* **Data Persistence:** Demonstrates how to save data (coordinates) to the MongoDB database.
* **Data Retrieval:** Shows how to fetch data from the database.
* **TCP Communication:** Illustrates basic inter-service communication using TCP-based NestJS microservices.
* **Event-Based Communication:** Introduces the concept of defining events for communication between microservices.

## Tech Stack

* **[NestJS](https://nestjs.com/)**: A progressive Node.js framework for building efficient and scalable server-side applications.
* **[MongoDB](https://www.mongodb.com/)**: A NoSQL document database used for storing application data.
* **[Mongoose](https://mongoosejs.com/)**: An elegant MongoDB object modeling for Node.js.
* **[Docker](https://www.docker.com/)**: A platform for developing, shipping, and running applications in isolated environments called containers.
* **[Docker Compose](https://docs.docker.com/compose/)**: A tool for defining and managing multi-container Docker applications.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

* **[Node.js](https://nodejs.org/)** (version >= 16.0.0)
* **[npm](https://www.npmjs.com/)** (usually installed with Node.js) or **[yarn](https://yarnpkg.com/)**
* **[Docker](https://www.docker.com/get-started)** (if you plan to use Docker for database setup)
* **[Docker Compose](https://docs.docker.com/compose/install/)** (if you plan to use Docker Compose)

## Setup

Follow these steps to set up and run the project:

### Setting up the NestJS Microservices Project

## Getting Started

1.  Clone this repository (if it were a public repository).
2.  Follow the steps in the [Setup](#setup) section to configure your environment and database.
3.  Explore the code structure and the implemented features.
4.  Run the NestJS application(s) and any associated microservices.

## Contributing

Contributions are welcome! If you have suggestions, bug reports, or would like to add new features, please feel free to open an issue or submit a pull request.

## License

[MIT](LICENSE) (Replace with your project's license if applicable)