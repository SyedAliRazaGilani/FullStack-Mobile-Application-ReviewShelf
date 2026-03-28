<h1 align="center">FullStack Mobile Application - ReviewShelf</h1>

## 🎯 React Native Full Stack Mobile App

📱 ReviewShelf is a full-stack React Native mobile app for sharing book reviews. 

👤 Users can sign up/login, create posts with book titles, ratings, cover images, and captions, view a home feed with infinite scrolling, see their profile with their posts, and delete posts. 

🌐 Built with React Native/Expo Router (frontend) and Node.js/Express/MongoDB (backend), with image uploads via Cloudinary.

---

## 🧑‍🍳 App Features Overview

- 🔐 **Auth** — signup & login with JWT, error handling for bad creds
- 🏠 **Home Feed** — newest‑first posts with **infinite scrolling**
- ➕ **Create Post** — title, rating, cover image & caption (all required)
- 👤 **Profile Screen** — user info + their posts
- 🗑️ **Delete Post** — confirmation alert before removal
- 🎨 **4 instant themes** — just swap one color object
- 🌐 **Web support** — run on `localhost` in the browser
- 🚪 **Logout**

---

## 🧠 Features Details

- ⚙️ Build a REST API with **Node.js**, **Express** & **MongoDB**
- 🔑 Implement stateless auth using **JSON Web Tokens (JWT)**
- 🔄 Add performant **infinite loading** with pagination cursors
- 🖼️ Handle image uploads the easy way (base64 → Cloudinary)
- 🛫 Deploy the backend **for free** (Render / Railway)
- 🌍 Ship a cross‑platform app with **React Native + Expo Router**
- 🧭 Animate navigation & shared element transitions
- 🧪 Debug on a physical phone—no Android Studio or Xcode needed

---

## 🛠️ Technologies Used

### Frontend (Mobile)
- **React Native** (0.76.7) - Cross-platform mobile framework
- **Expo** (~52.0.38) - Development platform and toolchain
- **Expo Router** - File-based routing system
- **React Navigation** - Navigation library
- **Zustand** - State management
- **React** (18.3.1) - UI library
- **Expo Modules** - Image picker, file system, and other native features

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **MongoDB** - Database (via Mongoose)
- **JWT** (jsonwebtoken) - Authentication tokens
- **Cloudinary** - Image upload and storage
- **bcryptjs** - Password hashing
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variable management

---

## 📁 Run Code & .env Setup 

### ⚙️ Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=<YOUR_MONGO_DB_URI>
JWT_SECRET=<YOUR_VERY_HARD_TO_FIND_SECRET>

CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_CLOUD_NAME>
CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_API_SECRET>

API_URL=<YOUR_DEPLOYED_API_URL>
```

## ⚙️ Run the backend

```bash
cd backend
npm install
npm run dev

```

## 📱 Run the mobile

```bash
cd mobile
npm install
npx expo
```

---

**Author:** Ali Gilani
