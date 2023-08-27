# ToDoList MERN Backend

This is the backend for the ToDoList MERN (MongoDB, Express, React, Node.js) application. It provides the necessary APIs to manage and manipulate ToDo items stored in a MongoDB database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/ToDoList-MERN-Backend.git
   ```

2. Navigate to the project directory:

   ```
   cd ToDoList-MERN-Backend
   ```

3. Install the required dependencies using npm:

   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your MongoDB connection URL:

   ```
   MONGODB_URL=your_mongodb_connection_url_here
   ```

## Usage

1. Start the server:

   ```
   npm start
   ```

2. The server will start and connect to the MongoDB database. You will see a message indicating a successful connection to the database.

3. The API endpoints are now available for use.

## API Endpoints

The backend provides the following API endpoints:

- `GET /` - Retrieves all ToDo items.
- `POST /save` - Saves a new ToDo item.
- `POST /update` - Updates a ToDo item.
- `POST /delete` - Deletes a ToDo item.

Refer to the [todoroutes.js](/routes/todoRoutes.js) file for more details about the API routes and their corresponding controller functions.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a pull request to the original repository.

## License
