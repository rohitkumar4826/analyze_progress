# Video Progress Tracker

A full-stack web application for tracking video playback progress with real-time synchronization capabilities. Built with React frontend and Node.js/Express backend, featuring WebSocket integration for live updates.

---

🚀 **Live Demo:**  
[https://analyze-progress-1.onrender.com/](https://analyze-progress-1.onrender.com/)

---

## 📋 Table of Contents

- [Features](#-features)  
- [Tech Stack](#-tech-stack)  
- [Project Structure](#-project-structure)  
- [Prerequisites](#-prerequisites)  
- [Installation & Setup](#-installation--setup)  
- [Environment Variables](#-environment-variables)  
- [Usage](#-usage)  
- [API Documentation](#-api-documentation)  
- [Deployment](#-deployment)  
- [Contributing](#-contributing)  
- [License](#-license)  
- [Acknowledgments](#-acknowledgments)  

---

## ✨ Features

- Real-time Progress Tracking: Track video playback progress with live updates  
- WebSocket Integration: Real-time synchronization across multiple clients  
- RESTful API: Comprehensive endpoints for progress management  
- Interval Merging: Intelligent merging of overlapping progress intervals  
- In-Memory Storage: Fast, lightweight data persistence  
- Cross-Platform: Works on desktop and mobile browsers  
- Responsive Design: Optimized for various screen sizes  

---

## 🛠 Tech Stack

### Frontend

- React - User interface library  
- JavaScript (ES6+) - Programming language  
- CSS3 - Styling and responsive design  
- WebSocket Client - Real-time communication  

### Backend

- Node.js - JavaScript runtime environment  
- Express.js - Web application framework  
- WebSocket (`ws`) - Real-time bidirectional communication  
- CORS - Cross-origin resource sharing  

---

## 📁 Project Structure

analyze-progress/
├── client/ # React frontend application
│ ├── public/
│ ├── src/
│ │ ├── progress.js/
│ │ └── App.js
│ ├── package.json
│ └── .env.production
├── server/ # Node.js backend server
│ ├── server.js
│ ├── package.json
├── README.md
└── .gitignore


---

## 📋 Prerequisites

Make sure you have the following installed on your machine before running the application:

- [Node.js](https://nodejs.org/) (v16.0.0 or higher)  
- [npm](https://www.npmjs.com/) (v7.0.0 or higher)  
- [Git](https://git-scm.com/) (for cloning the repository)  

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://git@github.com:rohitkumar4826/analyze_progress.git
cd video-progress-tracker

2. Backend Setup
Navigate to the `server` directory and install dependencies:
cd server
npm install

3. Frontend Setup
Navigate to the `client` directory and install dependencies:
cd client
npm install
```

### Start the Backend and Frontend server respectively:
```bash
node server.js or nodemon server.js
npm start
npm run dev
```
## Demo Images
![anal1](https://github.com/user-attachments/assets/a0391a4a-b793-4911-94da-ac908d03c3d8)
![anal2](https://github.com/user-attachments/assets/73f7207b-cadd-4d35-ae2f-e3ee885cafd1)










