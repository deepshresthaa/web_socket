# Web Socket Chat Application

This project demonstrates the basics of WebSockets using a simple real-time chat application built with Node.js, Express, and Socket.io.

## Features

- Real-time messaging between connected users
- Simple frontend interface for sending and displaying messages
- Uses Socket.io for WebSocket communication

## Getting Started

### Prerequisites

- Node.js installed

### Installation

1. Clone the repository or download the source code.
2. Install dependencies:

   ```sh
   npm install
   ```

### Running the Application

Start the server:

```sh
node app.js
```

Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

## Project Structure

- `app.js` - Main server file (Express + Socket.io)
- `public/index.html` - Frontend HTML for chat interface
- `package.json` - Project metadata and dependencies

## How It Works

- The server serves the static frontend and handles WebSocket connections.
- When a user sends a message, it is broadcast to all connected clients in real-time.

## Learning Outcome

This project is a basic introduction to WebSockets and real-time communication in web applications.

## License

ISC