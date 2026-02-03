# Express.js MongoDB Setup with Auth

A boilerplate for Express.js with MongoDB integration, now featuring full authentication using JWT and Bcrypt.

## Features

- **Express.js**: Fast, unopinionated, minimalist web framework.
- **MongoDB & Mongoose**: Object modeling for Node.js.
- **Authentication**: Secure registration and login using JWT.
- **Password Hashing**: Bcryptjs for secure password storage.
- **Middleware**: Protected routes with token validation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mgalihpp/express-mongodb-setup.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and add your credentials:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   ```
4. Run the application:
   ```bash
   npm start
   ```

## API Endpoints

### Auth
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login and get token
- `GET /api/auth/user` - Get current user (Private)

## License
ISC
