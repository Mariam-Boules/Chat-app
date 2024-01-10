## Chat App

A simple chat application built with Node.js, Express, and Socket.io. This application enables users to join chat rooms, send messages, and share their locations in real-time.

### Modules

1. **`messages.js`:**
   - Provides functions for generating chat messages and location messages.
   - Usage example: `const { generateMessage, generateLocationMessage } = require('./messages');`

2. **`users.js`:**
   - Manages user-related functionalities, including adding, removing, retrieving users, and getting users in a specific room.
   - Usage example: `const { addUser, removeUser, getUser, getUsersInRoom } = require('./users');`

3. **`index.js`:**
   - The main server script that sets up the server, handles WebSocket connections, and manages chat functionalities.
   - Dependencies: `path`, `http`, `express`, `socket.io`, `bad-words`, `./utils/messages`, `./utils/users`.
   - Usage: Run the server with `npm start` and visit [http://localhost:3000](http://localhost:3000) to start chatting.

### Usage

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the server:**
   ```bash
   npm start
   ```

Visit the application at [http://localhost:3000](http://localhost:3000) and enjoy chatting in real-time!
