# Real-Time Location Tracker

This is a simple real-time location tracking web application built using **Socket.IO**, **Geolocation API**, and **Leaflet.js**.  
It tracks users' live locations and displays them on a map in real time.

---

## Features

- Real-time location sharing using Socket.IO  
- Live map updates using Leaflet.js  
- Automatic marker update when user moves  
- Removes marker when a user disconnects  
- Uses browser Geolocation API  

---

## Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Node.js, Express.js  
- Real-time Communication: Socket.IO  
- Map Library: Leaflet.js  
- Map Provider: OpenStreetMap  

---

## How It Works

1. The browser accesses the user's location using `navigator.geolocation`
2. Latitude and longitude are sent to the server via Socket.IO
3. Server broadcasts location to all connected clients
4. Each client updates or creates markers on the map
5. When a user disconnects, their marker is removed

---

##
---

## How to Run the Project

### Clone the repository
```bash
git clone https://github.com/your-username/repo-name.git
npm install
npm start

```
## Requirements

1. Node.js installed
2. Internet connection (for OpenStreetMap tiles)
3. Browser permission for location access
---
## License

1. This project is licensed under the MIT License
2. you are free to use this repo  and integrate into your own projects as a feature.
---

