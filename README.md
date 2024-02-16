# Full-Stack React App README
This is a full-stack React application designed to provide a comprehensive user experience with features such as user authentication, profile management, post handling, bookmarks, and settings.

# Installation
To run this application locally, follow these steps:
Clone the repository:
git clone <repository-url>

# Navigate to the project directory:
cd <project-directory>

# Install dependencies:
npm install

# Set up the server:
Ensure that the backend server is configured and running.

Start the application:
npm start
This command will start both the frontend and backend servers.

# Usage
The application provides the following features:

Login: Access the application by navigating to /login.  (username: charan, password: charan@2024) (After successful login a JWT Token will be generated for authenticating the user and the token will be stored in chrome browser with name 'jwt_token' in Application/Cookies section. after successful logout the user will be redirected to login page and the JWT Token will be removed from the cookies.)

Profile Page: View and manage user profiles.
Posts: Manage user posts.
Bookmarks: Access and manage bookmarked posts.
Settings: Configure application settings.

# Project Structure
components: Contains React components used throughout the application.
LoginRoute: Components related to user authentication and login.
App.css: Stylesheet for the application.
App.js: Entry point of the React application.
index.js: JavaScript file responsible for rendering the React application.

# Routing
This application uses React Router for client-side routing. Here are the main routes:

/login: Login Page
/: Profile Page
/profile/posts: User Posts
/profile/bookmarks: Bookmarked Posts
/settings: Application Settings

# Backend Integration
Ensure that the backend server is set up and running. The frontend communicates with the backend for user authentication and data retrieval.

# Dependencies
This project depends on the following packages:

react: JavaScript library for building user interfaces.
react-router-dom: Routing library for React applications.
