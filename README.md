# WebRTC Project

This project is a basic WebRTC application that demonstrates peer-to-peer video communication using WebSockets for signaling. The project is containerized using Docker and Docker Compose.

## Repository

GitHub: [https://github.com/radheyyyyyy/webrtc](https://github.com/radheyyyyyy/webrtc)

## Project Structure

- **frontend**:  
  Contains the React-based frontend application.  
  - Navigate to `/sender` to access the sending side.  
  - Navigate to `/receiver` to view the received video stream.

- **backend**:  
  Contains the WebSocket server used for signaling between the sender and receiver.

## Technologies Used

- **React** with Vite for the frontend
- **WebSocket** for signaling communication
- **WebRTC** for peer-to-peer video communication
- **Docker** and **Docker Compose** for containerization

## Getting Started

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed on your machine
- [Docker Compose](https://docs.docker.com/compose/install/) installed
- Node.js and npm (for local development and building images)

### Setup & Running the Application

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/radheyyyyyy/webrtc.git
   cd webrtc
   npm i
   docker compose up -d
   npm run dev
