# Real-Time Chat System with Go and React

A simple real-time chat application using WebSockets with a Go backend and a React frontend.

## Project Overview

This project sets up a basic WebSocket server in Go and a React client for real-time message exchange. The server echoes messages sent by the client, demonstrating bidirectional communication.

## Prerequisites

- **Go**: To run the WebSocket server.
- **Node.js** and **npm**: For the React frontend.
- Go package **github.com/gorilla/websocket**.

## Installation and Setup

### Backend Setup

1. **Clone the Repository** and navigate to the `backend` directory:
   ```bash
   git clone <repo-url>
   cd backend
   ```

2. **Install WebSocket Dependency**:
   ```bash
   go get github.com/gorilla/websocket
   ```

3. **Run the WebSocket Server**:
   ```bash
   go run main.go
   ```
   The server should start on `http://localhost:8080`.

### Frontend Setup

1. **Navigate to the Frontend Directory**:
   ```bash
   cd frontend
   ```

2. **Install React Dependencies**:
   ```bash
   npm install
   ```

3. **Start the React Application**:
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Usage

1. Start the backend server in the `backend` directory (`http://localhost:8080`).
2. Start the frontend app in the `frontend` directory (`http://localhost:3000`).
3. Use the app interface to send messages, which are echoed back by the server and displayed in the browser console.

## Troubleshooting

- **WebSocket Connection Errors**: Ensure the backend server is running before starting the frontend.
- **CORS Issues**: The WebSocket server is configured to allow all origins for development. Adjust this for production as necessary.

[## License]:#

[This project is licensed under the MIT License.]:#
