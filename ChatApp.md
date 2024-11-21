## Overview

**Project Title**:

**Project Description**:
A simple real-time chat application developed using Flutter for the frontend and WebSocket for 
communication. The app allows users to send and receive messages in real time. The WebSocket server
is built with Node.js to handle the communication between the Flutter app and clients.  

**Project Goals**:

Demonstrate the integration of WebSocket for real-time communication in a mobile app.
Build a responsive user interface with Flutter.
Create a working WebSocket server with Node.js to handle messages.
Host and document the entire project on GitHub.

## Instructions for Build and Use

Steps to build and/or run the software:

1. Clone the repository:
git clone https://github.com/tafara-marava/Real-Time-Chat-App.git

2. Navigate to the Flutter project directory:
cd chat_app

3. Install dependencies:
run the command "flutter pub get" in your terminal.

4. Run the WebSocket server (Node.js):
cd chat_server && node server.js

5. Run the Flutter app:
flutter run (Make sure the iOS or Android emulator is running)


Instructions for using the software:

1. Open the Flutter app on your emulator or device.
2. Type a message into the text field at the bottom of the screen.
3. Press the send button to send the message. The message will appear in the chat window and also
be logged on the server. 

## Development Environment 

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* Flutter 3.7.0 (or latest stable version)
* Dart SDK 3.0.0
* Node.js 18.x or later
* WebSocket package for Flutter (web_socket_channel)
* WebSocket library for Node.js (ws)

## Useful Websites to Learn More

I found these websites useful in developing this software:

* Flutter Documentation
* WebSocket Documentation
* Node.js Documentation

## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* [ ] Add user authentication to the chat app.
* [ ] Implement the ability to send multimedia files (images, audio).
* [ ] Improve error handling and validation for the WebSocket connection.

