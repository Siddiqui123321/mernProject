# mernProject

My MERN Application
This is a simple MERN (MongoDB, Express, React, Node.js) application with user authentication and a dashboard displaying dummy data.

Table of Contents
Getting Started
Prerequisites
Installation
Running the Application
Usage
Contributing
License
Getting Started
Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v14 or higher)
MongoDB (Community Edition)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/my-mern-app.git
Navigate to the backend directory:

bash
Copy code
cd my-mern-app/myapp-backend
Install backend dependencies:

bash
Copy code
npm install
Navigate to the frontend directory:

bash
Copy code
cd ../myapp-frontend
Install frontend dependencies:

bash
Copy code
npm install
Running the Application
Start the MongoDB server:

bash
Copy code
# Navigate to MongoDB bin directory (adjust the path)
cd "C:\Program Files\MongoDB\Server\{version}\bin"

# Start MongoDB server with data directory
mongod --dbpath "C:\data"
Start the backend server:

bash
Copy code
# Navigate to the backend directory
cd my-mern-app/myapp-backend

# Start the backend server
npm start
Start the frontend:

bash
Copy code
# Navigate to the frontend directory
cd ../myapp-frontend

# Start the frontend
npm start
The application should now be accessible at http://localhost:3000 in your web browser.

Usage
Open the application in your web browser and sign up with a new account.
Log in with your credentials to access the dashboard.
The dashboard displays dummy data and includes a graph and a list of data.
Click the logout button to log out and invalidate the JWT token.
Contributing
Contributions are welcome! If you find any issues or want to contribute to the project, feel free to create a pull request.
