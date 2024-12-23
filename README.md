# File Sharing System

A real-time file sharing and communication platform built for BCIIT (Banarsidas Chandiwala Institute of Information Technology). This system enables secure, room-based file transfers and messaging between users, making it ideal for educational environments where quick file sharing between students and teachers is essential.

## About The Project

The File Sharing System was developed as a minor project to address the need for simple, secure file sharing in educational settings. The system operates on a room-based mechanism where users can create or join private rooms using unique room IDs, ensuring that files and messages are only shared with intended recipients.

The application features separate interfaces for senders and receivers, with a clean, intuitive design that makes it easy for users to:
- Share files of any type instantly
- Send real-time messages within rooms
- Monitor file transfer status
- View sharing history within the current session

Security and privacy are maintained through isolated rooms, and the system automatically manages storage by cleaning up files when sessions end.

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript
- Backend: Node.js, Express.js
- Real-time Communication: Socket.IO
- File Handling: Multer
- Auto Browser Launch: Open package

## Prerequisites

Before you begin, ensure you have:
- Node.js (v14 or higher)
- npm (typically comes with Node.js)
- A modern web browser
- Basic understanding of terminal/command prompt

## Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/smammar19/File-Sharing-System.git
cd File-Sharing-System
```

2. Install dependencies:
```bash
npm install
```

3. Create uploads directory:
```bash
mkdir uploads
```

4. Start the application:
```bash
npm start
```

The application will automatically launch in your default browser at `http://localhost:3000`

## How to Use

1. When the application launches, you'll see a welcome screen asking whether you're a sender or receiver
2. Choose your role:
   - Sender: Can create rooms and send files/messages
   - Receiver: Can join rooms and receive files/messages
3. Enter the same Room ID on both sender and receiver interfaces
4. Start sharing files and messages within your private room

## Project Structure
```
project-root/
├── public/            # Static files
│   ├── images/        # Image assets
│   ├── index.html     # Sender interface
│   ├── receiver.html  # Receiver interface
│   ├── welcome.html   # Landing page
│   └── style.css     # Styling
├── uploads/          # Temporary file storage
├── index.js         # Server configuration
└── package.json     # Project dependencies
```

## License

This project is licensed under the ISC License.

## Acknowledgments

Developed by Ammar.
