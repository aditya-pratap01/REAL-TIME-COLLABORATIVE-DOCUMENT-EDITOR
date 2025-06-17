# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR
# CodTech Internship Task 3 - Real-Time Collaborative Document Editor
Company Name : CODTECH IT SOLUTIONS

NAME : ADITYA PRATAP

INTERN ID : CT04DN802

DOMAIN : WEB DEVELOPMENT

DURATION 4 WEEKS

MENTOR : NEELA SANTOSH

## 📄 Overview
This project is developed as part of **CodTech Internship Task 3**, where the objective is to create a **Real-Time Collaborative Document Editor** using modern full-stack technologies. It allows multiple users to edit the same document at the same time with real-time synchronization. It works similarly to Google Docs, ensuring every participant sees live updates of the document as others type.

This project uses **React.js** and **Tailwind CSS** for the frontend, **Node.js** and **Express.js** for the backend, **Socket.IO** for real-time bi-directional communication, and **MongoDB** for data persistence.

## 🛠 Tech Stack
### Frontend:
- React.js (Vite-based setup)
- Tailwind CSS
- Socket.IO client

### Backend:
- Node.js
- Express.js
- Socket.IO server
- MongoDB with Mongoose
- CORS

## ✨ Features
- Real-time document collaboration
- Automatic content broadcasting to all clients
- Document persistence using MongoDB
- Clean and modern UI with Tailwind CSS
- Socket.IO used for ultra-fast data synchronization

## 📁 Folder Structure
```
collab-doc-editor/
├── client/                 # Frontend (React + Tailwind)
│   ├── src/
│   │   ├── App.jsx
│   │   ├── index.js
│   │   ├── index.css
│   │   └── main.jsx
│   └── tailwind.config.js
│
├── server/                 # Backend (Node.js + Socket.IO)
│   ├── index.js
│   ├── models/Document.js
│   └── package.json
│
└── README.md
```

## 🚀 How to Run the Project
### Prerequisites:
- Node.js and npm
- MongoDB installed and running locally

### Backend Setup:
```bash
cd server
npm install
npm start
```
The backend will run on `http://localhost:5000`

### Frontend Setup:
```bash
cd client
npm install
npm run dev
```
The frontend will run on `http://localhost:5173`

Ensure both frontend and backend are running before use.

## 🔁 How It Works
- When a user visits the app, they receive the latest saved version of the document.
- As the user types, their changes are sent to the backend using Socket.IO.
- The backend then broadcasts these changes to all other connected users.
- All clients update their textareas in real time.
- Meanwhile, the latest version is also stored in MongoDB.

## 📌 Example Use Case
Imagine two students working together on a project report. Both open this application, and as one types, the other sees updates instantly. Neither has to refresh the page or save manually—the system handles it all.

## 🔐 Future Enhancements
- Add user login and authentication
- Enable document sharing with custom IDs
- Allow creation of multiple documents
- Add version history and undo functionality
- Use CRDT/OT (like Yjs or Automerge) for conflict resolution

## 👨‍💻 Developed By
**Aditya pratap**  
As part of the internship program at **CodTech**, this was my third task to demonstrate real-time application building skills using full-stack JavaScript development.

## 🎓 Internship Notes
> This project is a valuable hands-on experience in developing collaborative apps with real-time features using Socket.IO and storing persistent content in Mongodb
>
> 📩 Contact Email: singhaditya83475@gmail.com

LinkedIn: Aditya Pratap

GitHub: aditya-pratap01
