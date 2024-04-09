## Chat Application with Flask-SocketIO

This repository contains a chat application built with Flask-SocketIO, allowing real-time communication between multiple clients. The application utilizes Flask for the backend and SocketIO for handling WebSocket connections.

### Features

- Real-time messaging between multiple clients.
- Dynamic display of active users in the chat.
- Clean and simple UI for sending and receiving messages.
- Automatic disconnection handling for clients leaving the chat.

### Repository Structure

- `main.py`: Flask-SocketIO application code for handling WebSocket communication and message broadcasting.
- `config.py`: Configuration file containing environment variables and Flask configuration.
- `client.py`: Client-side script for establishing a connection with the server and sending/receiving messages.
- `server.py`: Server-side script for managing client connections, broadcasting messages, and handling disconnections.
- `person.py`: Class representing a person in the chat, holding the client's IP address, socket client, and name.

### Usage

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Install the required Python libraries:

   ```bash
   pip install flask flask-socketio
   ```

3. Set up the server and client scripts according to your requirements.
4. Run the Flask-SocketIO server:

   ```bash
   python main.py
   ```

5. Open multiple client instances and connect to the server to start chatting in real-time.

### Dependencies

- [Flask](https://flask.palletsprojects.com/): Web framework for building web applications with Python.
- [Flask-SocketIO](https://flask-socketio.readthedocs.io/): Extension for integrating Socket.IO with Flask applications.

### Acknowledgments

- This project is based on Flask-SocketIO, which provides easy-to-use functionality for building real-time applications.
- Special thanks to the SocketIO library for simplifying WebSocket communication between the server and clients.

Feel free to explore, modify, and extend this project according to your requirements. If you have any questions or suggestions, please feel free to reach out!
