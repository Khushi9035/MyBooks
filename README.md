# Book Management 

Description
The Book Management System is a full-stack web application that allows users to manage a collection of books. Users can add, view, update, and delete books from the system. The backend is built with Node.js and Express, while the frontend is developed using React with Vite for faster builds and Tailwind CSS for styling.

Tech Stack<br/>
Backend: Node.js, Express<br/>
Frontend: React, Vite, Tailwind CSS<br/>
Database: MongoDB <br/>

#Installation and Setup <br/>
->Install Project Dependencies <br/>
In the root directory of the project, run the following command to install the required dependencies:<br/>
npm install

->Configure Database Connection<br/>
Navigate to the config. Update the MongoDB connection URL with your own MongoDB URL(or in .env file).<br/>
MONGO_URI=mongodb://<your-database-url>:<port>/<your-database-name><br/>

->Run the Backend Server
After configuring the database, switch to the backend directory and start the server using the following command:
npm start

->Run the Frontend (Client-Side) Application
Open a new terminal window and switch to the frontend folder (typically the client/ directory). Run the following command to start the frontend server:
npm run dev

->Check for Errors
If you encounter any errors during these steps, check the package.json file for missing dependencies or incorrect scripts. Ensure the proper scripts and dependencies are listed in both the backend and frontend package.json files.

Backend Example (package.json):
{
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
  }
}

Frontend Example (package.json):

{
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "dev": "vite"   // If you're using Vite for React or Vue.js
  }
}
