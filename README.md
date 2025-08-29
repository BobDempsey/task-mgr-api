# Task Manager API

This is a simple Task Manager API built using Node.js and Express.js

## Features

- Create, read, update, and delete tasks
- RESTful API design
- Lightweight and easy to extend

## Prerequisites

- [Node.js](https://nodejs.org/)
- [NPM](https://www.npmjs.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BobDempsey/task-mgr-api
   cd task-mgr-api
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the development server:

   ```bash
   npm run start
   ```

2. The API will be available at `http://localhost:3000`

## Scripts

- `npm start`: Start the development server with hot reload

## API Endpoints

| Method | Endpoint     | Description         |
| ------ | ------------ | ------------------- |
| GET    | `/tasks`     | Get all tasks       |
| POST   | `/tasks`     | Create a new task   |
| GET    | `/tasks/:id` | Get a task by ID    |
| PATCH  | `/tasks/:id` | Update a task by ID |
| DELETE | `/tasks/:id` | Delete a task by ID |

## License

This project is licensed under the [MIT License](LICENSE).
