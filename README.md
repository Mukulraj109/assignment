# 🎬 Strmly - Full Stack Video Sharing Platform

This repository acts as the **meta project** that brings together both the frontend and backend of the Strmly application — a simple full-stack video uploading and sharing platform.

---
<pre><code>## 📁 Project Structure <code> strmly/ ├── frontend/ # React.js client for user interface │ ├── public/ │ ├── src/ │ │ ├── components/ │ │ ├── pages/ │ │ ├── api.js │ │ └── main.jsx │ ├── .env │ └── package.json │ ├── backend/ # Express.js + MongoDB API and upload service │ ├── src/ │ │ ├── controllers/ │ │ ├── models/ │ │ ├── routes/ │ │ ├── utils/ │ │ ├── middlewares/ │ │ ├── app.js │ │ └── index.js │ ├── public/ │ ├── .env │ └── package.json </code> </pre>

---

## 🔗 Linked Repositories

- 🌐 Frontend Repo: [strmly-frontend](https://github.com/Mukulraj109/sterly-frontend.git)
- 🔧 Backend Repo: [strmly-backend](https://github.com/Mukulraj109/strmly-backend.git)

## 🚀 Getting Started


### 1. Clone frontend & backend
git clone https://github.com/yourusername/strmly-frontend.git frontend
git clone https://github.com/yourusername/strmly-backend.git backend

### 2. Install dependencies
cd frontend && npm install
cd ../backend && npm install

### 3. Set up environment variables
Create .env files in both frontend/ and backend/ directories.

📦 backend/.env
PORT=8000
MONGODB_URI=mongodb://localhost:27017/strmly
JWT_SECRET=your_jwt_secret
CORS_ORIGIN =*
ACCESS_TOKEN_SECRET = your_access_token
DB_NAME = your_db_name
REFRESH_TOKEN_SECRET = your_refersh_token
CLOUD_NAME=your_cloudinary_cloud
REFRESH_TOKEN_EXPIRY = 10d
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
CORS_ORIGIN=http://localhost:3000





### 🧰 Tech Stack
Frontend: React.js , Axios, CSS Modules

Backend: Node.js, Express.js, MongoDB, Mongoose

Uploads: Multer, Cloudinary

Auth: JWT

Security: Helmet, Rate Limiting

Extras: Pagination, Recommended videos, FFmpeg-ready



