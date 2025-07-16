# Travel and Tourism Management System MER


The project appears to be a **full-stack travel blog application** with both `backend` and `client` folders. 

* Overview
* Features
* Tech Stack
* Folder Structure
* Setup Instructions
* Scripts
* Environment Configuration

Here’s the generated `README.md`:


```markdown
# Travel Blog - Full Stack Application

A full-stack travel blogging platform that allows users to create, view, and interact with travel stories. This project is built using Node.js, Express, and MongoDB on the backend, and React.js with Vite on the frontend.

## 🌍 Features

- ✍️ Create, edit, and delete blog posts
- 🌆 Upload images for blog entries
- 🧭 Explore a feed of travel stories
- 🔒 User authentication (login/register)
- 📱 Responsive design

## 🚀 Tech Stack

### Frontend:
- React (Vite)
- Tailwind CSS
- Axios
- React Router

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer (for file uploads)
- Dotenv

## 📁 Project Structure

```

Travel-blog-main/
├── backend/               # Node.js/Express API
│   ├── index.js           # Main server entry
│   └── ...                # Routes, Controllers, Middleware, etc.
├── client/                # React frontend
│   ├── src/               # React source code
│   ├── public/
│   ├── index.html
│   └── ...
├── .env-sample            # Example environment config
├── README.md              # Project documentation
└── package.json           # Project metadata and dependencies

````

## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/travel-blog.git
cd travel-blog
````

### 2. Backend Setup

```bash
cd backend
npm install
cp .env-sample .env
# Update .env with your MongoDB URI and other configs
npm start
```

### 3. Frontend Setup

```bash
cd client
npm install
cp .env-sample .env
# Update frontend .env if needed (e.g., API URL)
npm run dev
```

## 🔐 Environment Variables

Create a `.env` file in both `backend/` and `client/` directories based on the provided `.env-sample`.

### Backend `.env`

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### Client `.env`

```
VITE_API_URL=http://localhost:5000
```

## 📜 Scripts

### Backend

| Script        | Description          |
| ------------- | -------------------- |
| `npm start`   | Start backend server |
| `npm run dev` | Start with nodemon   |

### Frontend

| Script          | Description            |
| --------------- | ---------------------- |
| `npm run dev`   | Start React app (Vite) |
| `npm run build` | Build for production   |

## 🤝 Contribution

Contributions are welcome! Feel free to submit issues or pull requests to improve this travel blog app.

---

**Author:** Your Name
**License:** MIT

```

Let me know if you'd like this saved to a file or customized with your name or GitHub link.
```


# Screenshots
![HomePage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/504bb803-217d-402a-9087-fed08986d6b1)
![BookPackagePage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/9733432f-e462-4eff-819e-66cba510c8b6)

# Admin Panel
![Screenshot (23)](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/8b4409ab-d8a5-4fd8-bc3d-987667fba72c)
![AddPackageAdminPage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/79c05dd8-45f8-477d-801d-6d1432e042fe)
![AllPaymentsAdminPage](https://github.com/Sanjayng125/MERN-Travel-Tourism-App/assets/106653066/de0963bf-3f1b-47c4-ab0f-bbae33371150)


