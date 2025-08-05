# 📍 Live Real-Time Location Sharing App

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

A real-time location sharing web application built using **Node.js**, **Socket.IO**, **Leaflet.js**, and the **Geolocation API**. Users can share their live location with others and view all connected users on an interactive map.

---

## 🚀 Features

- 🔄 Real-time location updates using WebSockets (Socket.IO)
- 📍 Live map visualization with Leaflet.js and OpenStreetMap
- 🌐 Uses Geolocation API to track user’s live position
- 👥 Multi-user support with unique markers for each user
- 📱 Responsive design for mobile and desktop
- ⚙️ Powered by an Express.js server and EJS templating

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed

### Installation

```bash
# Clone the repository
git clone https://github.com/SimerdeepSingh4/RealTime_Tracker.git

# Navigate into the project directory
cd RealTime_Tracker

# Install dependencies
npm install

# Start the server
npm start

5.  Open your browser and go to `http://localhost:3000`.

---
```

## 📁 Folder Structure
```
REALTIME-TRACKER/
├── public/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
├── views/
│   └── index.ejs
├── app.js
├── package.json
└── README.md
```

---

## 🌍 Deployment

You can deploy this project on any platform that supports Node.js and WebSockets, such as:

- [Render](https://render.com/)
- [Railway](https://railway.app/)
- [Cyclic](https://www.cyclic.sh/)
- [Fly.io](https://fly.io/)

For deployment, ensure your code uses the `PORT` environment variable provided by the platform.

```javascript
const PORT = process.env.PORT || 3000;
server.listen(PORT, () => {
  console.log(`Server is running on port ${PORT}`);
});
```

---

## 🧠 Future Improvements

- [ ] **User Authentication:** Add usernames, avatars, and login functionality.
- [ ] **Private Rooms:** Create private rooms for sharing locations with specific people.
- [ ] **Location History:** Save and view location history using a database like MongoDB.
- [ ] **Shareable Links:** Generate unique links to share locations.
- [ ] **Distance Calculation:** Show the distance between users in real-time.

---

## 🙋‍♂️ Author

**Simerdeep Singh Gandhi**

- Portfolio: [https://simerdeep-portfolio.vercel.app/](https://simerdeep-portfolio.vercel.app/)
- GitHub: [@SimerdeepSingh4](https://github.com/SimerdeepSingh4)
- LinkedIn: [Simerdeep Singh Gandhi](https://www.linkedin.com/in/simerdeep-singh-gandhi-5569a7279/)

---

## ✨ Show Your Support

Give a ⭐️ if this project helped you!