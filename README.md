# Video Chat Application

A real-time video chat application built using WebRTC, Node.js, and Socket.io. This project allows users to connect and communicate via video in real-time.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Features
- Real-time video and audio communication
- Multiple user connections
- Simple and intuitive user interface
- Works on most modern web browsers

## Technologies Used
- **WebRTC**: For real-time communication.
- **Node.js**: Server-side JavaScript environment.
- **Socket.io**: For handling real-time communication between clients and server.
- **HTML/CSS**: For the frontend user interface.
- **JavaScript**: For client-side scripting.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Saurabhtcet/video-chat-app.git
Navigate to the project directory:

cd video-chat-app

Install the dependencies:

npm install

Start the servee
npm start

Open your web browser and navigate to:
http://localhost:3000
Share the room URL with your friends to start chatting!
How It Works
Signaling: The application uses Socket.io to handle the signaling process required for establishing WebRTC connections between peers.
Peer Connections: When two users connect, a peer connection is created using WebRTC, allowing audio and video streams to be shared in real-time.
User Interface: A simple web interface displays the video streams and allows users to connect easily.
