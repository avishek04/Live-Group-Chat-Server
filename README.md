# MSD CS6011 - Chat Server Assignment

## Overview
The chat server allows multiple clients to connect, send, and receive messages in real time.

## Features
- Supports multiple clients simultaneously
- Clients can send and receive messages in real time
- Uses sockets for communication
- Simple text-based protocol for messaging

## Prerequisites
To run this project, ensure you have the following installed:
- Java 8+ (if using Java)

## Installation
Clone the repository:
```sh
git clone https://github.com/avishek04/Live-Group-Chat-Server.git
cd chat-server
```

### Java Setup
```sh
javac Server.java
java Server
```

## Usage
1. **Start the server:**
   ```sh
   java Server       # For Java
   ```
2. **Connect a client:**
   ```sh
   java Client       # For Java
   ```
3. **Send and receive messages** between multiple connected clients.

## Architecture
- The **server** listens for client connections on a specified port.
- Each client runs on a separate thread/process.
- Messages are broadcasted to all connected clients.

## Future Improvements
- Add authentication for users
- Implement a WebSocket-based UI
- Store chat history in a database
- Improve error handling

## Contributors
- Avishek Choudhury (https://github.com/avishek04)
