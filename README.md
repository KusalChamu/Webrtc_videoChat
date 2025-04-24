# WebRTC Video Chat Application

This is a real-time video conferencing web application built using **WebRTC**, **HTML**, **CSS**, and **Node.js**. It allows users to initiate peer-to-peer video/audio calls directly from their browsers without the need for any plugins.

## 🔍 Features

- 📹 Real-time video and audio communication
- 💬 Chat messaging between peers
- 🖥️ Screen sharing functionality
- 🔒 Secure signaling using WebSockets and Node.js
- 🌐 Responsive and modern UI with custom layout

## 🛠️ Technologies Used

- WebRTC for peer-to-peer communication
- Node.js + Express for the backend signaling server
- Socket.io for real-time signaling
- HTML, CSS for the frontend interface

## 🚀 Live Demo

> If hosted: [Click here to view the live demo](https://youtu.be/jFsKI0WS2-U)


## 🧑‍💻 Installation

## 🧑‍💻 Installation

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Webrtc_videoChat.git
   cd Webrtc_videoChat
2.Install dependencies
```bash
npm install
```
3.Run the program
```bash
npm run dev
```
4.Open the app
Go to your browser and navigate to:

```bash
http://localhost:3000
```

## 💡 How It Works

- When a user joins a room, a signaling connection is established with the server using **Socket.io**.
- **WebRTC** is used to create a direct peer-to-peer connection between the users.
- Users can:
  - Share audio and video in real-time.
  - Send and receive chat messages.
  - Share their screen with other participants.
- All interactions happen seamlessly within the browser, enhancing the overall conferencing experience.


🙋‍♂️ Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
