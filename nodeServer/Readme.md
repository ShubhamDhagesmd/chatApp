# Real-Time Chat Application

This is a simple real-time chat application built using Node.js, Express, and Socket.io.

## Features

- Real-time messaging between multiple users
- Basic UI for sending and receiving messages

## Installation
- Clone this repository:
   
   git clone https://github.com/ShubhamDhagesmd/chatApp
   cd chatApp

### How it Works
- The server is set up using Node.js and Express to serve the chat interface.
- Socket.io is used for real-time communication between the server and clients.
- Each new user connection triggers a 'connection' event, allowing messages to  be broadcasted to all users connected to the server.
- It is just like any messagener app.

## Structure
- index.js: Entry point of the application, sets up the server and Socket.io.
- index.html: HTML file for the chat interface.
- styles.css: CSS file for styling the chat interface.

## Usage
- Start the server using the following command: 'nodemon index.js' 
Ensure the server remains running while chatting.

- Run the 'client.js' file with 'goLive' option:- This will open the chat interface in your default browser and prompt for a username for chat identification.

- Copy and paste the chat interface URL into a new tab/window to add more users to the chat room.

Interact with the chat interface:- Once multiple users are connected, type messages in the chat input field. Messages will be displayed in real-time for all users in the same chat room. 

----Enjoy chatting with others in real-time!

Feel free to create as many users as needed for testing purposes.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or create a pull request.