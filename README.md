# Node.js User Authentication Template

This repository provides a template for a Node.js application with user authentication using JWT tokens. It follows best practices for security and code organization.

## Features

- User registration
- User login
- Password update
- Email update
- Phone number update
- Account deletion
- JWT-based authentication
- Rate limiting to prevent brute-force attacks
- Secure HTTP headers with Helmet
- Input validation and error handling

## Technologies Used

- Node.js
- Express.js
- MongoDB with Mongoose
- JWT (JSON Web Tokens)
- bcrypt for password hashing
- dotenv for environment variables
- Helmet for security
- HPP for HTTP parameter pollution prevention
- Morgan for logging
- Express-rate-limit for rate limiting

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/node-auth-template.git
   cd node-auth-template