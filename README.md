# Polling App - Backend

## 📌 Overview

This project is the **backend** for a real-time polling system that allows teachers to create live polls and students to participate in them. The backend is built with **Node.js**, **Express.js**, and **MongoDB** for data storage. **Socket.IO** is used for real-time communication between clients and the server.

---

## ⚙️ Tech Stack

- **Node.js** (with Express.js for server-side logic)
- **MongoDB** (for database storage)
- **Socket.IO** (for real-time bi-directional communication)

---

## 🧰 Backend Setup

### ✅ Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (Developed with version `v22.5.1`)
- [npm](https://www.npmjs.com/)
- [MongoDB Community Server](https://www.mongodb.com/try/download/community)

---

### 🚀 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/alok2608/polling-backend.git
cd polling-backend
```

2. **Install dependencies:**

```bash
npm install
```

3. **Start MongoDB** (in a separate terminal or as a service):

```bash
mongod
```

4. **Start the backend server:**

```bash
npm start
```

---

## 🌐 Running the Application

The backend will be available at:

```
http://localhost:3000
```

The frontend communicates with the backend using **Socket.IO** and **REST API endpoints** for managing polls.

---

