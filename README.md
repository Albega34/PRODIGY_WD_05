
# Social 📸

A full-stack social media web application built with Node.js, Express, MongoDB, and modern frontend technologies. Users can register, log in, upload posts, like, comment, and interact just like Instagram.

---

## 🌐 Features

- 🧑‍🤝‍🧑 User authentication (signup/login)
- 📷 Upload and view posts with captions
- 💬 Add and view comments
- ❤️ Like/unlike posts
- 📨 Real-time messaging (basic)
- 🛡️ Middleware authentication with JWT

---

## 🛠️ Tech Stack

### Backend:
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication
- Multer (file upload)
- Socket.IO (chat)

### Frontend:
- React.js (Assumed based on project structure)

---

## 📁 Project Structure

```
instaclone-main/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── middlewares/
│   ├── index.js
├── frontend/
│   └── (React app files if present)
├── package.json
```

---

## 🚀 How to Run

### Prerequisites:
- Node.js and npm
- MongoDB (local or cloud)

### Clone the Repository

```bash
git clone https://github.com/yourusername/instaclone.git
cd instaclone-main
```

### Install Dependencies

```bash
npm install
cd backend
npm install
```

### Set up `.env` file

Create a `.env` file in the `backend/` directory and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Start the Backend

```bash
node index.js
```

### Start the Frontend

```bash
cd frontend
npm install
npm start
```

---

## 📸 Screenshots

Add screenshots of the login page, dashboard, post feed, and messaging UI here.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---
