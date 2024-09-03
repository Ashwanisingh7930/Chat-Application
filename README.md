# Online Chat Application using MERN Stack
Welcome to the Online Chat Application project! This application is built using the MERN stack (MongoDB, Express, React, Node.js). Follow the instructions below to set up and run the application on your local machine.

## Getting Started
Prerequisites
Before you begin, ensure you have the following installed on your system:
* Node.js (includes npm)
* MongoDB (for local database)
## Clone the Repository
To get started, clone the repository using the following command:
`gh repo clone Ashwanisingh7930/Chat-Application`
## Setup the Backend
Navigate to the API Folder:
`cd Chat-Application/api`
## Install Dependencies:

Run the following command to install the necessary dependencies:
`npm install`
<br> If you encounter any issues, try running:
`npm install --force`
<br> Configure Environment Variables:

Create a .env file in the root of the api folder and add the following content:
`MONGO_URL=mongodb://localhost:27017/chatapp`
<br>Replace chatapp with the name of your MongoDB database if different.

## Start the Backend Server:

Run the following command to start the backend server:
` npm start `
<br>Alternatively, if you use Yarn, you can run:
`yarn start`
## Setup the Frontend
Navigate to the Public Folder:<br>
`cd ../public`
## Install Dependencies:
Run the following command to install the necessary dependencies:
`npm install`
## Start the Frontend Server:
`npm start`
This will open the application in your default web browser.<br>
Frontend: Access the chat application by visiting http://localhost:3000 in your web browser.<br>
Backend: The backend server will run on http://localhost:5000.
## Troubleshooting
* Common Errors: If you face issues during setup, ensure that all dependencies are correctly installed and that your MongoDB server is running.
* Support: For additional help, feel free to open an issue on the GitHub repository.
## Contributing
Contributions are welcome! Please follow the standard GitHub flow:

Fork the repository.
1. Create a new branch (`git checkout -b feature-branch`).
2. Commit your changes (`git commit -am 'Add new feature'`).
3. Push to the branch (`git push origin feature-branch`).
4. Create a new Pull Request.

## Acknowledgements
* [MERN Stack](https://mern.js.org/)
* [React](https://react.dev/)
* [Node.js](https://nodejs.org/en)
* [Express](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)
