# Stock Watch

Stock Watch is an open-source inventory management application built with the MERN (MongoDB, Express, React, Node.js) stack. It provides a simple and efficient way to track and manage product stock levels.

## Features

- Product management (add, edit, delete)
- Real-time stock level tracking
- User-friendly interface with material design
- Search and filter capabilities
- Responsive design for various screen sizes

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14 or later)
- npm (v6 or later)
- MongoDB (v4 or later)

## Project Structure

The project is divided into two main directories:

- `backend`: Contains the Express.js server and API
- `frontend`: Contains the React application

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/stock-watch.git
   cd stock-watch
   ```

2. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```
   cd ../frontend
   npm install
   ```

4. Create a `.env` file in the `backend` directory and add your MongoDB connection string and other environment variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
   ```

## Running the Application

1. Start the backend server:
   ```
   cd backend
   npm run dev
   ```
   The server should now be running on `http://localhost:5000`.

2. In a new terminal, start the frontend development server:
   ```
   cd frontend
   npm start
   ```
   The frontend application should now be running on `http://localhost:3000`.

## Usage

After starting both the backend and frontend, you can:

1. Add new products to your inventory
2. Update stock levels
3. Search for specific products
4. Edit or delete existing products

## Contributing

We welcome contributions to Stock Watch! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Commit your changes using the [Conventional Commits](https://www.conventionalcommits.org/) standard
5. Push to your fork: `git push origin feature/your-feature-name`
6. Create a pull request

Please make sure your code adheres to our coding standards and include unit tests for new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please open an issue on GitHub.

Thank you for your interest in Stock Watch!
