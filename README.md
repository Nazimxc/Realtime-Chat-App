# ChatCord - Real-time Chat Application

ChatCord is a real-time chat application built using **Node.js**, **Express**, **Socket.io**, and **Redis**. It allows users to join chat rooms and communicate in real-time.

## Features
- Real-time messaging using **Socket.io**
- User-specific chat rooms
- User join/leave notifications
- Redis-based **Socket.io adapter** for scalability

## Installation

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or later recommended)
- [Redis](https://redis.io/) (Running locally on port 6379)

### 1. Clone the repository
```sh
git clone https://github.com/yourusername/chatcord.git
cd chatcord
```

### 2. Install dependencies
```sh
npm install
```

### 3. Set up environment variables
Create a `.env` file in the root directory and add:
```ini
PORT=3000
REDIS_URL=redis://127.0.0.1:6379
```

### 4. Start Redis server
Ensure that Redis is running:
```sh
redis-server
```

### 5. Start the application
```sh
node server.js
```
Or using **nodemon** for development:
```sh
npx nodemon server.js
```

## Usage
1. Open a browser and go to `http://localhost:3000`.
2. Enter a username and room name to join a chat.
3. Start chatting with other users in the same room.

## Project Structure
```
chatcord/
│── public/           # Static files (HTML, CSS, JavaScript)
│── utils/            # Helper functions for messaging and user management
│── server.js         # Main server file
│── .env              # Environment variables
│── package.json      # Dependencies and scripts
│── README.md         # Project documentation
```

## Dependencies
- **express** - Web framework for Node.js
- **socket.io** - WebSockets for real-time communication
- **redis** - In-memory database for message handling
- **dotenv** - Loads environment variables

## License
This project is open-source and available under the **MIT License**.

## Contributing
Feel free to contribute! Fork the repository and submit a pull request.

## Contact
For any questions or support, reach out via [your email or GitHub profile].

