## Music Share
Music Share is a web application for sharing and managing your favorite tracks and playlists. It is built using the MERN (MongoDB, Express, React, Node.js) stack and allows users to create and share playlists, as well as browse and listen to tracks uploaded by other users.

# Features
-User authentication: Users can create an account, log in, and logout.<br/>
-Track management: Users can upload and manage their own tracks, as well as browse and listen to tracks uploaded by them.<br/>
-Playlist management: Users can create and manage playlists, add tracks to playlists.<br/>
-Search functionality: Users can search for tracks by keyword.<br/>

## Getting Started
To get started with this application, follow these steps:

-Clone this repository to your local machine:
bash
-Copy code.<br/>
-git clone https://github.com/your-username/music-share.git<br/>
-Create a .env file in the backend directory and add the following environment variables:<br/>
    DB_USER=<MONGO_DB DB_USER><br/>
    DB_PASS=<MONGO_DB DB_PASS><br/>
    DB_NAME=<MONGO_DB DB_NAME><br/>
    JWT_SECRET=<YOUR_SECRET_KEY><br/>
-Create a .env file in the frontend directory and add the following environment variables:<br/>
    API_URL=<RUNNING_API_URL><br/>
-Install the required dependencies in both the frontend and backend directories:<br/>
-cd frontend<br/>
-npm install<br/>
-npm start<br/>
-cd ..<br/>
-cd backend<br/>
-npm install<br/>
-npm start<br/>

This will start the frontend and backend servers in development mode. If the application does not open automatically, navigate to http://localhost:3000 in your browser.<br/>

## Usage
To use the application, follow these steps:<br/>

-Create an account or log in to an existing account.<br/>
-Upload your own tracks or browse and listen to tracks uploaded by other users.<br/>
-Create playlists, add new playlists with multiple songs, add tracks to playlists.<br/>
-Search for tracks by track name and artist name.<br/>

## Technologies
This application is built using the following technologies:<br/>

-MongoDB: A document-oriented NoSQL database used for data storage.<br/>
-Express: A web framework for Node.js used for building the backend API.<br/>
-React: A JavaScript library used for building the frontend user interface.<br/>
-Node.js: A JavaScript runtime used for running the backend server.<br/>
-Render: A unified cloud  used to build, deploy and host my server.<br/>
-FireBase: A lightweight hosting platform used for hosting my frontend client.<br/>

## Screenshots
![image](https://user-images.githubusercontent.com/108655042/229369099-29ecd693-cca6-4d0e-9d14-885c335847b0.png)
![image](https://user-images.githubusercontent.com/108655042/229369251-bb98c81a-ca4f-4ea7-9003-b846807f22ac.png)
![image](https://user-images.githubusercontent.com/108655042/229369518-3b1d086e-db32-4eba-90db-9a29d51285bc.png)


## License
This project is licensed under the MIT License. See the LICENSE file for details.
