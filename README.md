# Whisper Wave

Whisper Wave is a real-time chat application built with Node.js, Express, and Socket.IO. It allows users to send and receive messages instantly in a seamless, user-friendly interface.

## Features

- Real-time communication with instant messaging
- User-friendly interface with automatic scrolling and message appending
- Client-side and server-side integration using Socket.IO
- Lightweight and efficient server setup with Express

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- Node.js
- npm (Node package manager)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Saptaneel/whisper-wave.git
    cd whisper-wave
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

### Running the Application

1. Start the server:
    ```bash
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000` to start using Whisper Wave.

## Project Structure

- `server.js`: Sets up the Express server and Socket.IO for handling real-time connections.
- `public/client.js`: Manages the client-side functionality for sending and receiving messages.
- `public/index.html`: The main HTML file that structures the chat interface.
- `public/style.css`: (Optional) Contains styles for the chat application interface.

## Usage

1. Upon opening the application, you will be prompted to enter your username.
2. Type your message in the textarea and press Enter to send.
3. Messages will be displayed in the chat area, with your messages appearing on the right and incoming messages on the left.

## Learnings

- Gained hands-on experience with real-time communication using Socket.IO.
- Enhanced skills in Node.js and Express.js for backend development.
- Improved understanding of client-server architecture and web socket integration.

## Contributing

Feel free to fork this repository and make improvements. Pull requests are welcome.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
