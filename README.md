# NewsProfileApp

This is a full-stack React application with backend demonstrating authentication using React Router.

#Installation
Clone the repository to your local machine:

git clone https://github.com/your-username/react-router-authentication.git


#Navigate to the project directory:
cd react-router-authentication

#Install dependencies using npm or yarn:
npm install

or

yarn install

#Usage
#To run the application locally, execute the following command:

npm start
This will start the development server and open the application in your default web browser.

#Structure
src/: Contains the application source code.
components/: Contains React components.
LoginRoute/: Contains components related to authentication and user profile. 
NotFound.js: Component rendered when the requested route does not match any defined routes.
App.js: Main component responsible for routing.
App.css: CSS styles for the application.
public/: Contains public assets and the HTML template.

#Dependencies
React: A JavaScript library for building user interfaces.
react-router-dom: Declarative routing for React applications.
js-cookie: A simple, lightweight JavaScript API for handling cookies.

#Routes
/login: Login page where users can authenticate.  (username: charan, password: charan@2024) (After successful login, a JWT Token will be generated and will be stored in chrome browser as a cookie and will be removed after successful logout )
/: Profile page displayed after successful login.
/profile/posts: Page displaying user posts.
/profile/bookmarks: Page displaying user bookmarks.
/settings: Settings page where users can configure preferences.
/*: Default route for handling 404 errors.
