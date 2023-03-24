## Music Share
Music Share is a web application for sharing and managing your favorite tracks and playlists. It is built using the MERN (MongoDB, Express, React, Node.js) stack and allows users to create and share playlists, as well as browse and listen to tracks uploaded by other users.

# Features
-User authentication: Users can create an account, log in, and logout.
-Track management: Users can upload and manage their own tracks, as well as browse and listen to tracks uploaded by them.
-Playlist management: Users can create and manage playlists, add tracks to playlists.
-Search functionality: Users can search for tracks by keyword.

## Getting Started
To get started with this application, follow these steps:

-Clone this repository to your local machine:
bash
-Copy code
-git clone https://github.com/your-username/music-share.git
-Create a .env file in the backend directory and add the following environment variables:
    DB_USER=<MONGO_DB DB_USER>
    DB_PASS=<MONGO_DB DB_PASS>
    DB_NAME=<MONGO_DB DB_NAME>
    JWT_SECRET=<YOUR_SECRET_KEY>
-Create a .env file in the frontend directory and add the following environment variables:
    API_URL=<RUNNING_API_URL>
-Install the required dependencies in both the frontend and backend directories:
-cd frontend
-npm install
-npm start
-cd ..
-cd backend
-npm install
-npm start

This will start the frontend and backend servers in development mode. If the application does not open automatically, navigate to http://localhost:3000 in your browser.

## Usage
To use the application, follow these steps:

-Create an account or log in to an existing account.
-Upload your own tracks or browse and listen to tracks uploaded by other users.
-Create playlists, add new playlists with multiple songs, add tracks to playlists.
-Search for tracks by track name and artist name.

## Technologies
This application is built using the following technologies:

-MongoDB: A document-oriented NoSQL database used for data storage.
-Express: A web framework for Node.js used for building the backend API.
-React: A JavaScript library used for building the frontend user interface.
-Node.js: A JavaScript runtime used for running the backend server.
-Render: A unified cloud  used to build, deploy and host my server.
-FireBase: A lightweight hosting platform used for hosting my frontend client.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
