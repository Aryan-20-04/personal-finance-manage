# 💼 Personal Finance Management Tool

A full-stack personal finance tracker that helps you manage expenses by category, visualize spending with charts, and track your monthly budget with intelligent alerts.

Built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and styled using Material UI.

## 📸 Demo
pfm-tool/demo.png

## ✨ Features

* ✅ User Authentication with JWT
* 💸 Add, delete, and filter expenses
* 🯞 Create and manage custom categories
* 📊 Visualize spending with pie charts (Recharts)
* ⚠️ Smart budget alerts
* 🌙 Light/Dark Mode toggle
* 🎛️ Rate limiting and security headers (Helmet)
* 🧠 Token-based auto-login and protected routes
* 🌐 Responsive UI (Material UI)

## ⚖️ Tech Stack

Frontend:

* React.js
* Material UI
* Axios
* Recharts

Backend:

* Node.js
* Express.js
* MongoDB with Mongoose
* JWT Authentication
* Express Rate Limit
* Helmet, Compression, Morgan

## 📁 Folder Structure

```
pfm-tool/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── public/
│   └── src/
│       ├── auth/
│       ├── pages/
│       ├── components/
│       └── App.js
```

## ⚙️ Getting Started

### Prerequisites

* Node.js & npm
* MongoDB (local or cloud via MongoDB Atlas)

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/pfm-tool.git
cd pfm-tool
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a .env file:

.env

PORT=5000
MONGO\_URI=your\_mongodb\_uri
JWT\_SECRET=your\_secret\_key

Start backend:

```bash
npm run dev
```

### 3. Frontend Setup

In another terminal:

```bash
cd frontend
npm install
npm start
```

The app will run at [http://localhost:3000](http://localhost:3000)

## 🚀 Deployment

You can deploy the backend using Render, Railway, or Heroku, and the frontend using Vercel or Netlify.

Make sure to:

* Set environment variables on the server.
* Set the frontend’s API base URL to the deployed backend.

## 🧪 API Endpoints

Base: /api

* POST /auth/register
* POST /auth/login
* GET /expenses
* POST /expenses
* DELETE /expenses/\:id
* GET /categories
* POST /categories
* DELETE /categories/\:id

All endpoints (except /auth/\*) are protected via JWT.

## 🛆 Requirements

See: requirements.txt

## 📄 License

MIT

## 🤛🏼‍♂️ Author

Aryan Sinha
Feel free to connect on LinkedIn or star the repo!
