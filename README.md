# Vue.js & Socket.IO Real-Time Chat App (Starter Template)

## Overview  
**Vue.js & Socket.IO Real-Time Chat App** is a starter template for building interactive, real-time communication applications.  
It combines a **Node.js + Socket.IO** backend for WebSocket-based messaging with a **Vue 3 + Vite** frontend for a responsive, modern UI.

This template provides the foundational structure for creating chat rooms, private messaging, or live collaboration tools.

## Why this project exists  
This project was created to:  
- Demonstrate integration of **Socket.IO** with a Node.js backend.  
- Showcase how to connect a **Vue.js** frontend to a WebSocket server.  
- Provide a minimal, clean starting point for building real-time applications.  
- Allow recruiters to see familiarity with event-driven architecture.

## Features  
- **WebSocket Communication** — Real-time, bidirectional messaging between client and server.  
- **Node.js Backend** — Powered by Express and Socket.IO.  
- **Vue.js Frontend** — Built with Vite for fast development and HMR (Hot Module Replacement).  
- **Scalable Structure** — Easily extendable for chat rooms, notifications, or multiplayer features.

## Technologies used  
- **Backend:** Node.js, Express, Socket.IO  
- **Frontend:** Vue.js 3, Vite  
- **Runtime:** npm for package management

## How to run the project  

### Backend  
```bash
cd chatServer
npm install
node chatServer.js
```

### Frontend  
```bash
cd chatClient
npm install
npm run dev
```

Visit the URL shown in the terminal to open the app in your browser.

## Dependencies & requirements  
- Node.js 16+  
- npm (comes with Node.js)  
- Modern browser with JavaScript enabled

## How to contribute  
1. Fork the repository and create a feature branch.  
2. Add features like chat rooms, user authentication, or message history.  
3. Submit a pull request describing your changes.

## What powers the core functionality?  
- **Socket.IO** — Handles real-time communication over WebSockets.  
- **Express** — Serves the backend API and Socket.IO connection.  
- **Vue.js** — Provides reactive UI updates in the frontend.
