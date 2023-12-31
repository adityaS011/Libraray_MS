# Library Management System

This project is a simple Library Management System implemented using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB Atlas account (for cloud-based database)

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/Library_MS.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd library-management-system
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Set up environment variables:**

    Create a `.env` file in the root directory and add the following:

    ```env
    PORT=3001
    DB_URI=your-mongodb-atlas-url
    SECRET_KEY=your-secret-key
    ```

    Replace `your-mongodb-atlas-url` with the connection URL from your MongoDB Atlas account, and set a secure value for `SECRET_KEY`.

5. **Run the application:**

    ```bash
    npm start
    ```

    The application will be accessible at `http://localhost:3001`.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

