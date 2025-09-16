Forty4 Frontend & Backend Assignment
This repository contains a full-stack user management application. It's built with a React.js frontend for the user dashboard and a Node.js REST API for data handling.

Features
Frontend (User Dashboard)
Dashboard View: Displays a list of all users.

User Details Page: Shows detailed information for a single user.

Search Functionality: Allows searching for users by name.

CRUD Operations: A form to add, update, and delete users.

Responsive Design: Styled with Tailwind CSS for various screen sizes.

Backend (User Management API)
RESTful API: Provides a complete set of CRUD endpoints for user data.

Database: Uses SQLite, a lightweight, file-based database.

Validation: Includes basic validation for required fields.

Error Handling: Returns appropriate HTTP status codes and messages.

Tech Stack
Frontend
React.js: For building the UI.

React Router DOM: For client-side routing.

Axios: For making API calls.

Tailwind CSS: For styling.

Backend
Node.js & Express.js: For the server and API framework.

SQLite3: The database driver.

CORS: Middleware to handle cross-origin requests.

Nodemon: For automatic server restarts during development.

Project Structure
The project is divided into two main directories:

user-dashboard/: Contains the complete React frontend.

user-management-api/: Contains the complete Node.js backend API.

Getting Started
Prerequisites
Node.js (LTS version recommended)

npm (comes with Node.js)

Step 1: Clone the Repository
Bash

git clone <your-repository-url>
cd <your-repository-name>
Step 2: Set Up the Backend
Navigate to the backend directory:

Bash

cd user-management-api
Install dependencies and start the server:

Bash

npm install
npm start


Step 3: Set Up the Frontend
Open a new terminal and navigate to the frontend directory:

Bash

cd user-dashboard
Install dependencies and start the app:


POST	/	Create a new user.
PUT	/:id	Update an existing user.
DELETE	/:id	Delete a user.
