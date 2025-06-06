# Collaborative Todo List App

A collaborative todo list application built with Electron and Firebase.

## Features

- Create and manage multiple todo lists
- Real-time collaboration with other users
- Google authentication
- Real-time task synchronization
- User-specific lists

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Create a Firebase project:
   - Go to [Firebase Console](https://console.firebase.google.com)
   - Create a new project
   - Enable Authentication (Google Sign-In)
   - Enable Realtime Database
   - Copy your Firebase configuration

3. Update Firebase configuration:
   - Open `src/firebase.js`
   - Replace the placeholder values with your Firebase configuration

4. Run the application:
```bash
npm start
```

## Usage

1. Sign in with your Google account
2. Create a new list by clicking "Create New List"
3. Add tasks to your list
4. Share the list ID with others to collaborate
5. Tasks will sync in real-time across all connected devices

## Technologies Used

- Electron
- Firebase (Authentication and Realtime Database)
- HTML5, CSS3, JavaScript

## License

MIT License