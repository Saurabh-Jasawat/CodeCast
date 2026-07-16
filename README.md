# CodeCast – Real-Time Collaborative Code Editor

CodeCast is a full-stack real-time collaborative code editor that enables multiple users to write, edit, and collaborate on code simultaneously in shared rooms. The application provides real-time synchronization using Socket.IO, a CodeMirror-powered editor, language selection, and a responsive user interface for seamless collaboration.

## Features

- Real-time collaborative code editing
- Shared coding rooms
- Live synchronization using Socket.IO
- CodeMirror-powered code editor
- Language selection
- Responsive user interface
- Multi-user collaboration

## Tech Stack

### Frontend
- React.js
- CodeMirror
- CSS

### Backend
- Node.js
- Express.js
- Socket.IO

## Project Structure

```
CodeCast
│
├── client
│   ├── public
│   ├── src
│   │   ├── components
│   │   │   ├── Client.js
│   │   │   ├── Editor.js
│   │   │   ├── EditorPage.js
│   │   │   └── Home.js
│   │   ├── App.js
│   │   ├── Socket.js
│   │   ├── Constants.js
│   │   ├── index.js
│   │   └── index.css
│   ├── package.json
│   └── README.md
│
├── server
│   ├── index.js
│   ├── Constants.js
│   ├── package.json
│   └── test.js
│
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/codecast.git
```

### Install Client Dependencies

```bash
cd client
npm install
```

### Install Server Dependencies

```bash
cd ../server
npm install
```

### Run Backend

```bash
npm start
```

### Run Frontend

```bash
cd ../client
npm start
```

## Future Enhancements

- Authentication
- File Management
- Code Execution Support
- Chat System
- Voice Collaboration
- Theme Switching

## Contributors

This project was developed as a group project. My contributions included frontend development, feature integration, and collaborative implementation.
