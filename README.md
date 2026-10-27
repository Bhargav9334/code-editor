# 🧑‍💻 Online Code Editor

> A browser-based HTML, CSS and JavaScript playground powered by Monaco Editor — write code, preview it live, then save and share it.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Monaco Editor](https://img.shields.io/badge/Monaco_Editor-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

## 📖 Overview

A CodePen-style online code editor. It gives you three Monaco editors (the same editor that powers VS Code) for HTML, CSS and JavaScript, renders the result in a live preview, and lets you save a snippet to the server and share it with a link. Snippets can also be downloaded as a JSON file.

## ✨ Features

- **Three Monaco editors** for HTML, CSS and JavaScript with a VS Code dark theme
- **Live preview** of your code as you type
- **Save & share** — snippets are stored on the server and shared through a unique link
- **Load shared snippets** directly from the URL
- **Download** your code as a JSON file
- Simple Express REST API (`POST /save`, `GET /load/:id`)

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| Frontend | React, Vite, @monaco-editor/react, React Router, Axios |
| Backend | Node.js, Express, UUID |
| Hosting | Render (API) |

## 📁 Project Structure

```
code-editor/
├── backend/
│   ├── snippets/     # Saved code snippets
│   └── server.js     # Save / load API
└── frontend/
    └── src/
        ├── App.jsx       # Editors, live preview, save & share
        └── main.jsx
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

```bash
git clone https://github.com/Bhargav9334/code-editor.git
cd code-editor
# Backend
cd backend
npm install
node server.js

# Frontend (in a new terminal)
cd frontend
npm install
npm run dev
```

## 👤 Author

**Bhargav Sinha** — Software Engineer · Full-Stack MERN Developer

- GitHub: [@Bhargav9334](https://github.com/Bhargav9334)
- Portfolio: [portfolio-blush-sigma-22.vercel.app](https://portfolio-blush-sigma-22.vercel.app)
- Email: bhargavsinha93@gmail.com

If you found this project useful, consider giving it a ⭐
