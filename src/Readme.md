# ChatSphere

ChatSphere is a Java-based multi-client chat application developed using TCP socket programming and multithreading.

The application follows a client-server architecture where the server must be started first. Once the server is running, multiple clients can connect to the server and communicate with each other through the command line.

ChatSphere supports public broadcast messaging, private messaging, multiple simultaneous clients, and command-based communication.

## 📌 Project Overview

ChatSphere is designed to demonstrate the fundamentals of network programming and client-server communication using Java.

The project focuses on practical implementation of:

- Client-server architecture
- TCP socket programming
- Java `ServerSocket` and `Socket`
- Multithreading
- Multiple simultaneous client connections
- Broadcast messaging
- Private messaging
- Client connection and disconnection handling
- Command-based message processing
- Java input/output streams

The current version is a console-based application developed primarily for learning and understanding Java networking concepts.

## ✨ Features

- Client-server communication using TCP sockets
- Multiple clients can connect to the same server
- Separate thread for each connected client
- Public broadcast messaging
- Private messaging between clients
- Server notifications when clients join or leave
- Online user information
- Command-based message handling
- Client exit functionality
- Console-based communication

## 🛠️ Technologies Used

- Java
- Java Socket Programming
- TCP/IP
- Multithreading
- ServerSocket
- Socket
- BufferedReader
- PrintWriter
- Scanner
- ArrayList
- Git
- GitHub

---

## 📂 Project Structure

ChatSphere/
│
├── ChatServer.java
├── ChatClient.java
├── README.md
└── .gitignore
