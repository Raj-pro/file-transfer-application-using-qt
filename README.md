# C++ File Transfer Application Using Qt

## Overview
This project is a C++ File Transfer Application built using the Qt framework. It enables a main server to communicate with multiple client servers, allowing users to send and receive text and image files seamlessly.

## Features
- **Client-Server Architecture:** One main server with support for multiple clients.
- **Bidirectional Communication:** Clients and the server can exchange text and image files.
- **User-Friendly Interface:** Intuitive GUI built with Qt for easy interaction.
- **Real-time Data Transfer:** Efficient and reliable file transfer between clients and the server.

## Technologies Used
- **Programming Language:** C++
- **Framework:** Qt (for GUI and networking)

## Demo
![Application Screenshot]([assets/screenshot.png](https://github.com/Raj-pro/file-transfer-application-using-qt/blob/main/image.png))

## Installation

### Clone the Repository
```bash
git clone https://github.com/your-username/Cpp-file-transfer-application-using-QT.git
```

### Open the Project in Qt Creator
1. Install Qt if you don't have it.
2. Open the `.pro` files in Qt Creator.

### Build the Project
1. Select the appropriate kit.
2. Build both the server and client projects.

### Run the Server and Clients
1. Start the server application first.
2. Run the client applications to connect to the server.

## Usage

### Start the Server
```bash
cd QTCPServer
./QTCPServer
```

### Connect Clients
```bash
cd QTCPClient
./QTCPClient
```

### Send Files
- Use the GUI to select and send text or image files.
- Received files will be displayed or saved in the designated folder.

## Project Structure
```
├── QTCPClient
│   ├── QTCPClient.pro
│   ├── QTCPClient.pro.user
│   ├── main.cpp
│   ├── mainwindow.cpp
│   ├── mainwindow.h
│   └── mainwindow.ui
├── QTCPServer
│   ├── QTCPServer.pro
│   ├── QTCPServer.pro.user
│   ├── main.cpp
│   ├── mainwindow.cpp
│   ├── mainwindow.h
│   └── mainwindow.ui
├── README.md
├── readme
└── assets
    └── screenshot.png
```

## Future Enhancements
- **File Transfer Progress Bar**
- **Encryption for Secure File Transfer**
- **Support for Additional File Types**
- **Drag and Drop Functionality**
