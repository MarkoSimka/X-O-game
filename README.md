# X/O (Tic Tac Toe) Game

This is a simple X/O (Tic Tac Toe) game that leverages Firebase for authentication and database services. This README file provides an overview of the project and instructions for setting up Firebase.

##  Project Description

This project is built with TypeScript and Firebase. It allows two players to play against each other in real-time using Firebase's real-time database. The game utilizes Firebase's onSnapshot method to listen for changes in the game state and updates the UI accordingly.

##  Features
  *  Real-time gameplay using Firebase's real-time database.
  *  Player authentication and management using Firebase Authentication.
  *  TypeScript for type-safe development.
  *  Firebase Cloud Functions for backend logic (if applicable).

##  Getting Started

To get started with this project, follow these steps:

1.Clone the repository:

    https://github.com/MarkoSimka/X-O-game.git //https

    git@github.com:MarkoSimka/X-O-game.git //ssh

2.Install Dependencies:

    cd xo-game
    yarn

3.Set Up Firebase:
  * Create a new Firebase project on the [Firebase Console](https://console.firebase.google.com).
  * Enable Firebase Authentication and Firebase Realtime Database.
  * Obtain your Firebase config object.

4.Configure Firebase:
  *  Replace the Firebase config in src/firebase.ts with your own Firebase config.
  *  Set up Firebase Authentication providers as per your requirements.

5.Start the Development Server:

    yarn start

6.Open the application
Open your browser and navigate to http://localhost:3000 to view the application.


##  Firebase Services

###  Real-time Database
The game uses Firebase's real-time database to store and synchronize game state between players. Firebase's onSnapshot method is used to listen for changes in the database and update the UI in real-time.

###  Authentication
Firebase Authentication is used to authenticate players and manage player sessions. Players can sign up, log in, and log out using various authentication providers supported by Firebase.

##  Contributing
Contributions are welcome! If you have any ideas, enhancements, or bug fixes, feel free to open an issue or submit a pull request.

Happy coding!
