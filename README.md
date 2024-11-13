# Real-Time Device Tracker

This project is a real-time web application that tracks the location of devices on an interactive map. Using geolocation and Socket.io, it provides live updates of device positions, enabling seamless tracking and visualization on the front end.

### Live Demo
Check out the live version of the app [**here**](https://realtimedevicetracker-f9jv.onrender.com).

You can open the link on multiple devices to see how the real-time location tracking works across different devices simultaneously. The app dynamically updates the location of all connected devices on the map in real time.
Future improvements will be added, which can be found in the [**Upcoming Enhancements**](#upcoming-enhancements) section.

## Features
- Real-time device tracking with instant updates using **Socket.io**.
- Interactive map with zooming and panning capabilities powered by **Leaflet.js**.
- Simple and intuitive user interface built using **EJS**, **HTML**, and **CSS**.
- Location updates are pushed to all connected users dynamically.

## Tech Stack
- **Frontend**: EJS, Leaflet.js, HTML, CSS
- **Backend**: Node.js, Express.js, Socket.io
- **Real-Time Communication**: Socket.io
- **Deployment**: Render

## Upcoming Enhancements
- **Session Management**: Enhancing user sessions for improved security.
- **Login Functionality**: Adding user authentication for better access control

## Getting Started

To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/manojkumarpangi/RealTimeDeviceTracker.git
2. Install the dependencies:
   ```bash
   npm install
3. Run the server:
   ```bash
    npm start
4. Access the app at http://localhost:3000.
