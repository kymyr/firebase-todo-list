# A Simple Todo-list made with React & Firebase

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Project Dependencies

The following packages were used in the project:

### `@mui/icons-material, @emotion/styled, @emotion/react, firebase, sass`

Prior to running, run the following command on the terminal:

### `npm i`

## Pre-requisites

### Firebase Web-app setup
1.) Setup a Firebase project at https://console.firebase.google.com
2.) Intialize a web-app for the project and go to the project settings and scroll down and select `config` under SDK setup and configuration.
3.) Copy the configuration and paste under the `Firebase configuration` section in `firebase.js` located in the src folder.

### Firestore setup
1.) After setting up the project via firebase, select `Firestore Database` under the build menu and initialize the Cloud Firestore for the database.
2.) Under the rules section, change the statement `allow read, write: if false;` to `allow read, write: if true;` to enable CRUD operations for the database. 
3.) Click Publish and we're done.

## To run the project,

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

