# 📝 WriteFlow - Blogging Application

WriteFlow is a full-stack blogging platform that allows users to create, read, update, and delete blog posts. It offers user authentication, image uploads, and a rich content editing experience — all built using modern web technologies.

## 🌐 Live Demo
🚧 *Coming Soon*  
<!-- You can uncomment the line below once hosted -->
<!-- [Live Preview](https://your-deployment-url.com) -->

---

## 🚀 Features

- 🧑‍💻 **User Authentication** (JWT-based)
- 📄 **Create, Edit, and Delete Blogs**
- 🖼️ **Image Upload Support**
- 🔐 **Secure Routes for Logged-In Users**
- 📂 **Static File Serving for Images**
- 📚 **Clean UI & Organized Structure**

---

## 🛠️ Tech Stack

### Frontend
- **HTML / EJS**
- **CSS**
- **Bootstrap**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB & Mongoose**
- **JWT Authentication**
- **Multer (for file uploads)**

---

## 📁 Project Structure

```
WriteFlow/
├── models/              # Mongoose schemas
│   ├── blog.js
│   └── comment.js
│
├── routes/              # Express route handlers
│   ├── blog.js
│   └── auth.js
│
├── public/              # Static files
│   └── uploads/         # Uploaded images
│
├── views/               # EJS templates
│
├── middlewares/
│   └── auth.js          # Auth cookie/token check
│
├── service/
│   └── authentication.js   
├── .env                 # Environment variables
├── index.js             # App entry point
└── package.json
```
## 📦 Installation
```
git clone https://github.com/OMENDRA1604/WriteFlow.git
cd WriteFlow
npm install
```
### Create a .env file in the root directory:
```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/writeflow
JWT_SECRET=yourSecretKeyHere
```
### Start the server:
```npm start```
### App will run at: 
http://localhost:3000
