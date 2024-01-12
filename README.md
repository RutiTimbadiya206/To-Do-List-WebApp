# To-Do-List-WebApp


This project is a ToDo List web application built using React for the frontend, Node.js for the backend, and MongoDB as the database.

## Features

- **User Authentication**: Secure user authentication system using JWT tokens.
- **Create, Read, Update, Delete (CRUD) Operations**: Manage your tasks with full CRUD functionality.
- **Real-time Updates**: Get real-time updates on task changes without refreshing the page.
- **Responsive Design**: Access and manage your ToDo list seamlessly on various devices.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js: [Download Node.js](https://nodejs.org/)
- MongoDB: [Install MongoDB](https://docs.mongodb.com/manual/installation/)
- npm: Install with `npm install -g npm`

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/todo-list-app.git
    cd todo-list-app
    ```

2. Install dependencies:

    ```bash
    cd client && npm install
    cd ../server && npm install
    ```

3. Set up environment variables:

    - Create a `.env` file in the `server` directory.
    - Add the following variables:

        ```env
        PORT=3001
        MONGO_URI=your_mongo_database_uri
        JWT_SECRET=your_jwt_secret
        ```

4. Run the application:

    ```bash
    # In the server directory
    npm start

    # In the client directory
    npm start
    ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the application.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
