# 🎥 Video-Match-App

## Description

Welcome to the Video Match App! 🎉

This is a fullstack real-time video chat application inspired by Omegle, built using React, WebRTC, Socket.IO, and Node.js. It allows two random users to connect via live video and chat instantly over peer-to-peer connections, with no registration required. This project demonstrates key real-time web technologies and how to coordinate frontend and backend for low-latency communication.

        💡 Future Plans: This project already includes backend integration, but future improvements will focus on scaling, authentication, reporting tools, and moderation features.

## Prerequisites

Before running Video Match App, ensure you have the following installed:

Node.js (Latest stable version recommended)

npm (Comes with Node.js)

You can install NodeJs : https://nodejs.org/fr/

## Installation

Clone the repository :

```
git clone https://github.com/gabrielgonta/video-match-app.git
```

Navigate to the root directory where the 'package.json' file is located, then run the command to install the dependencies :

```
cd video-match-app
```

## Deployment

1. Start the Client

```
cd client
npm install
npm run dev
```

2. Start the Server

```
cd ../server
npm install
npm start
```

By default, the client application runs on http://localhost:5173 :

## Features

        ✅ Random user matching
        ✅ Peer-to-peer video calling via WebRTC
        ✅ Real-time communication with Socket.IO
        ✅ Audio/video toggle and chat messaging
        ✅ Clean and responsive UI
        ✅ Separation of concerns (client/server folders)

## TechStack

- React.js – Frontend framework
- Tailwind CSS – Styling and responsive design
- Vite – Frontend build tool
- Socket.IO – Real-time bi-directional communication
- WebRTC – Peer-to-peer video and audio
- Node.js + Express – Backend server and socket handling

## Use Cases

This app is ideal for learning or extending into:

        🧑‍💻 Video chat platforms
        🛠 Real-time communication systems
        🎓 WebRTC training and experimentation
        👮 Anonymous communication systems with future moderation

## Future Scope

- Add user authentication (Google, GitHub login)
- User reporting and banning system
- Text-based chat enhancements (emojis, file sharing)
- Match filters (language, interests, location)
- Scalable WebSocket server with Redis
- WebRTC performance monitoring and analytics

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements:

Open an issue

Submit a pull request

## Authors

* **Gabriel Gonta** - *Initial work* - [video-match-app](https://github.com/gabrielgonta/video-match-app.git)