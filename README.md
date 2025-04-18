# TaskMaster Server

A robust and scalable task management server built with Node.js, Express, and MongoDB. This server provides a RESTful API for managing tasks with full CRUD operations.

## 🚀 Features

- **RESTful API** with comprehensive CRUD operations
- **MongoDB Integration** for reliable data persistence
- **CORS Support** for cross-origin requests
- **Environment Configuration** using dotenv
- **Error Handling** with appropriate status codes
- **MongoDB Atlas** integration with latest server API version

## 📋 API Endpoints

### Tasks

- `GET /tasks` - Retrieve all tasks
- `POST /tasks` - Create a new task
- `DELETE /tasks/:id` - Delete a specific task
- `PATCH /tasks/:id` - Update a specific task

## 🛠️ Technical Stack

- **Backend Framework**: Express.js
- **Database**: MongoDB
- **Runtime**: Node.js
- **Dependencies**:
  - express: ^4.18.2
  - mongodb: ^5.8.1
  - cors: ^2.8.5
  - dotenv: ^16.3.1
  - nodemon: ^3.0.1 (for development)

## ⚙️ Setup and Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Create a `.env` file with the following variables:
   ```
   PORT=5000
   DATABASE_URI=your_mongodb_uri
   ```
4. Start the development server:
   ```bash
   pnpm dev
   ```
5. For production:
   ```bash
   pnpm start
   ```

## 🔒 Security Features

- Environment variable protection
- MongoDB Atlas with strict API versioning
- Proper error handling and status codes
- CORS configuration for secure cross-origin requests

## 🧪 Testing

The server includes comprehensive error handling for:

- Database connection failures
- Invalid task IDs
- Missing resources
- Server errors

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
