# 🌍 Travel Blog – Full Stack Web Application

A modern full-stack travel blogging platform that lets users share their travel experiences through captivating stories and images. Designed with scalability, performance, and user experience in mind, this project uses a MERN-based architecture (MongoDB, Express, React, Node.js).



## ✨ Features

- 📝 **Create & Manage Blogs** – Add, edit, or delete travel stories with images.
- 📸 **Image Uploads** – Upload and showcase photos alongside each blog.
- 🔐 **User Authentication** – Secure login and registration system.
- 🌐 **Responsive Design** – Optimized for desktops, tablets, and mobile devices.
- ⚡ **Fast Frontend** – Built with Vite for a lightning-fast development experience.
- 📚 **Modular Codebase** – Clean and scalable folder structure.



## 🧰 Tech Stack

| Frontend                     | Backend                       | Database | Others        |
|-----------------------------|-------------------------------|----------|---------------|
| React + Vite                | Node.js + Express.js          | MongoDB  | Tailwind CSS  |
| React Router                | Multer (file uploads)         | Mongoose | Dotenv        |
| Axios                       |                               |          | JWT (optional)|



## 📁 Project Structure

```
Travel-blog-main/
│
├── backend/                # Express API backend
│   ├── index.js            # Entry point
│   └── routes/, controllers/, uploads/
│
├── client/                 # React frontend (Vite)
│   ├── src/                # App components and pages
│   ├── index.html          # HTML entry point
│   └── tailwind.config.js  # Tailwind CSS setup
│
├── .env-sample             # Sample environment file
├── package.json            # Root dependencies
└── README.md               # This file
```



## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/travel-blog.git
cd travel-blog
```

### 2. Setup Backend

```bash
cd backend
npm install
cp .env-sample .env   # Fill in your MongoDB URI
npm run dev           # Start development server
```

### 3. Setup Frontend

```bash
cd client
npm install
cp .env-sample .env   # Set API URL (e.g., http://localhost:5000)
npm run dev           # Launch frontend
```



## 🔐 Environment Variables

### Backend `.env`

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### Frontend `.env`

```
VITE_API_URL=http://localhost:5000
```



## 🚀 Available Scripts

### Backend

| Command       | Description                |
|---------------|----------------------------|
| `npm start`   | Start server (production)  |
| `npm run dev` | Start with live reload     |

### Frontend

| Command        | Description                 |
|----------------|-----------------------------|
| `npm run dev`  | Start dev server (Vite)     |
| `npm run build`| Build production frontend   |



## 🙌 Contribution Guide

Contributions are welcome! Here's how you can help:

- 🐛 Report bugs
- 📖 Improve documentation
- 🚀 Suggest or implement features

Feel free to fork the repo and open a pull request!



## 📄 License

MIT License — free for personal and commercial use.



## 👨‍💻 Author

**Your Name**  
Chinmayi Porla




