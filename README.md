Multi-User Task Application
This is a multi-user task application where each user can manage their own tasks by performing CRUD (Create, Read, Update, Delete) operations. The application provides features like pagination, filtering tasks based on completion status, and ensuring security measures such as password hashing and user authorization.
 <img src=" " >
Features
User Authentication: Users need to authenticate themselves to access the application. Passwords are securely hashed for user security.

Task Management: Each user can perform CRUD operations on their tasks, including creating new tasks, updating existing ones, marking tasks as completed, and deleting tasks.

Pagination: Tasks are paginated to improve the user experience and optimize loading times, especially when dealing with a large number of tasks.

Task Filtering: Users can filter their tasks based on completion status, allowing them to view completed or pending tasks separately.

Technologies Used
Frontend:
React.js
Axios (for making HTTP requests)
Backend:
Node.js with Express.js framework
MongoDB for database management
Mongoose (ODM library for MongoDB)
Backend Implementation
The backend of the application is built using Node.js and Express.js. It provides RESTful APIs for performing CRUD operations on tasks. It includes the following features:

User Authentication: Middleware to authenticate users using JWT (JSON Web Tokens).

Task Routes: Endpoints for handling CRUD operations on tasks, including pagination and filtering.

Task Model: MongoDB schema and model for defining task data structure.

Security Measures: Password hashing using bcrypt to securely store user passwords, and middleware to check user authorization before allowing CRUD operations on tasks.

Frontend Implementation
The frontend of the application is built using React.js. It interacts with the backend APIs to manage tasks and user authentication. It includes the following features:

User Authentication: Login and registration forms for user authentication, with password hashing before sending requests to the backend.

Task Management: Components for creating, updating, deleting, and viewing tasks. Pagination and filtering options are also available.

HTTP Requests: Axios library is used to make HTTP requests to the backend APIs for performing CRUD operations.

Getting Started
To run the application locally:

Clone this repository to your local machine.
Navigate to the backend directory and run npm install to install backend dependencies.
Start the backend server by running npm start.
Navigate to the frontend directory and run npm install to install frontend dependencies.
Start the frontend development server by running npm start.
Ensure that MongoDB is running locally on your machine or update the MongoDB connection URI in the backend configuration file.

Conclusion
The multi-user task application provides a secure and efficient way for users to manage their tasks. With features like user authentication, CRUD operations on tasks, pagination, and filtering, it offers a comprehensive solution for task management needs.
