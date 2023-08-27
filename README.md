# ToDoList MERN Backend

![Node.js](https://img.shields.io/badge/Node.js-v14.17.6-green)
![Express](https://img.shields.io/badge/Express-v4.17.1-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-yellow)
![License](https://img.shields.io/badge/license-MIT-orange)

This is the backend part of a MERN (MongoDB, Express.js, React.js, Node.js) ToDo List application. It provides the API endpoints required for managing tasks in the ToDo list.

## Getting Started

Follow these steps to set up and run the backend for the ToDo List application:

### Prerequisites

Make sure you have the following software installed on your system:

- [Node.js](https://nodejs.org/) (v14.17.6 or higher)
- [MongoDB](https://www.mongodb.com/) (Community Edition)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/M-YasirGhaffar/TodoList-MERN-backend.git
   ```

2. Navigate to the project directory:

   ```bash
   cd TodoList-MERN-backend
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and set the following environment variables:

   ```
   MONGODB_URL=<your-mongodb-connection-string>
   PORT=<port-number>
   ```

   Replace `<your-mongodb-connection-string>` with your MongoDB connection string and `<port-number>` with the desired port number.

### Usage

1. Start the server:

   ```bash
   npm start
   ```

   This will start the Express.js server, and you will see the message "Connected to MongoDB" in the console if the connection is successful.

2. The server will be running at `http://localhost:<port-number>`.

## API Endpoints

- **GET** `/`: Get a list of all ToDo items.
- **POST** `/save`: Create a new ToDo item.
  - Body: `{ "text": "Your task description" }`
- **POST** `/update`: Update an existing ToDo item.
  - Body: `{ "_id": "item-id", "text": "Updated task description" }`
- **POST** `/delete`: Delete a ToDo item.
  - Body: `{ "_id": "item-id" }`

## Contributing

Contributions are welcome! If you find any issues or want to add improvements, feel free to fork this repository and create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).