# CLAW - LegalTech Platform

CLAW - LegalTech Platform is a web application that facilitates communication and collaboration between clients, lawyers, and legal professionals. It allows clients to post legal gigs, connect with lawyers, and manage their cases efficiently.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
  - [Client Module](#client-module)
  - [Gig Module](#gig-module)
  - [Lead Module](#lead-module)
  - [Post Module](#post-module)
  - [User Module](#user-module)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB database

### Installation

1. Clone the repository: `git clone https://github.com/SanyamGoyal401/Claw.git`
2. Change to the project directory: `cd Claw`
3. Install dependencies: `npm install`
4. Set up the configuration files in the `config` folder.
5. Start the server: `npm start`

## Folder Structure

- `config`: Configuration files for the server and database.
- `controllers`: Handles the business logic for different modules.
- `middlewares`: Contains custom middleware functions.
- `models`: Defines the Mongoose models for the MongoDB database.
- `repositories`: Implements CRUD operations for different entities.
- `routes`: Contains the route definitions for different modules.
- `services`: Business logic for different modules.
- `utils`: Common utility functions and modules.

## Technologies Used

- Node.js
- Express.js
- MongoDB (Mongoose)
- bcrypt for password hashing
- JSON Web Tokens (JWT) for authentication

## Usage

### Client Module

- `/api/client/signup`: Create a new client account.
- `/api/client/login`: Sign in as a client.
- `/api/client/auth/me`: Get authenticated client details.

### Gig Module

- `/api/gig`: Get all gigs.
- `/api/gig/:id`: Get a specific gig by ID.
- `/api/gig/create`: Create a new gig.
- `/api/gig/update/:id`: Update an existing gig.
- `/api/gig/delete/:id`: Delete a gig.

### Lead Module

- `/api/lead`: Get all leads.
- `/api/lead/:id`: Get a specific lead by ID.
- `/api/lead/create`: Create a new lead.
- `/api/lead/update/:id`: Update an existing lead.
- `/api/lead/delete/:id`: Delete a lead.

### Post Module

- `/api/post`: Get all posts.
- `/api/post/:id`: Get a specific post by ID.
- `/api/post/create`: Create a new post.
- `/api/post/update/:id`: Update an existing post.
- `/api/post/delete/:id`: Delete a post.

### User Module

- `/api/user/signup`: Create a new user account.
- `/api/user/login`: Sign in as a user.
- `/api/user/auth/me`: Get authenticated user details.

## Contributing

We welcome contributions! Please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
