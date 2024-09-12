# Book Management 

**Description** <br/>
The Book Management System is a full-stack web application that allows users to manage a collection of books. Users can add, view, update, and delete books from the system. The backend is built with Node.js and Express, while the frontend is developed using React with Vite for faster builds and Tailwind CSS for styling.

**Tech Stack**<br/>
Backend: Node.js, Express<br/>
Frontend: React, Vite, Tailwind CSS<br/>
Database: MongoDB <br/>

**Installation and Setup** <br/>
->Install Project Dependencies <br/>
In the root directory of the project, run the following command to install the required dependencies:<br/>
_npm install_

->Configure Database Connection<br/>
Navigate to the config. Update the MongoDB connection URL with your own MongoDB URL(or in .env file).<br/>
_MONGO_URI=mongodb://<your-database-url>:<port>/<your-database-name>_<br/>

->Run the Backend Server<br/>
After configuring the database, switch to the backend directory and start the server using the following command:<br/>
_npm start_<br/>

->Run the Frontend (Client-Side) Application<br/>
Open a new terminal window and switch to the frontend folder (typically the client/ directory). Run the following command to start the frontend server:<br/>
_npm run dev_<br/>

->Check for Errors<br/>
If you encounter any errors during these steps, check the package.json file for missing dependencies or incorrect scripts. Ensure the proper scripts and dependencies are listed in both the backend and frontend package.json files.<br/>

Backend Example (package.json):<br/>
{<br/>
  "scripts": {<br/>
    "start": "node server.js",<br/>
    "dev": "nodemon server.js"<br/>
  }<br/>
}<br/>

Frontend Example (package.json):<br/>

{<br/>
  "scripts": {<br/>
    "start": "react-scripts start",<br/>
    "build": "react-scripts build",<br/>
    "dev": "vite"  <br/>
  }<br/>
}<br/>
