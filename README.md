
# TwitterClone 🐦🔥  
**MERN Stack | JWT Auth | Real-Time Social Experience**

A fully-featured Twitter-inspired microblogging platform with secure authentication, dynamic user interaction, and real-time communication. Built using the powerful MERN stack.

👉 **[Live Demo](#)** — *Explore it now!*

---

## ✨ Features

### 🔐 Authentication & Security
- JWT-based user authentication  
- ✉️ Email verification system  
- 🔄 Password reset & recovery  
- 🛡️ Role-based authorization (User / Moderator / Admin)  
- 🌐 *OAuth 2.0 integration (Coming Soon)*

---
###screenshot 
<h2>Home Page</h2>
![image](https://github.com/user-attachments/assets/72e036fb-e599-4147-8344-93296ac2084a)

<h2>Update Profile</h2>
![image](https://github.com/user-attachments/assets/3bc2a23e-b708-4394-b57c-79a10a992c37)


![image](https://github.com/user-attachments/assets/eb664f57-038c-4dad-a0be-948798609bd4)



### 🎯 User Experience
- 🌓 Light & Dark theme toggle  
- 🔍 Advanced tweet search with filters:
  - Hashtags  
  - User mentions  
  - Date range  
  - Engagement threshold (likes/retweets)  
- ⭐ Threaded tweet conversations  
- 🎯 Personalized tweet recommendations  

---

### 📝 Tweet System
- 💬 Rich text tweets with emoji & GIF support  
- 📸 Media uploads (images/videos via Cloudinary)  
- 🔁 Retweet with comments  
- 🔖 Bookmarking tweets  
- 📊 Tweet analytics (for verified users)

---

### 💬 Social Features
- 👥 Follow / Unfollow system  
- 💌 Real-time direct messaging (Socket.IO)  
- 🔔 Push notifications for:
  - New likes & retweets  
  - Mentions  
  - New followers  

---

## 🛠 Tech Stack

### 🔧 Frontend
- React.js (Hooks + Context API)  
- Redux Toolkit (State management)  
- React Router v6  
- Tailwind CSS + Dark Mode  
- Socket.IO Client (Real-time)  
- Lottie Animations

### 🔧 Backend
- Node.js & Express.js  
- MongoDB + Mongoose  
- JSON Web Tokens (JWT)  
- Nodemailer (email services)  
- Cloudinary (media uploads)

### 🔗 Services
- MongoDB Atlas  
- Vercel (Frontend Hosting)  
- Render (Backend Hosting)  
- Cloudinary CDN

---

## 🚀 Getting Started

### ✅ Prerequisites
- Node.js v18+  
- MongoDB Atlas cluster  
- Cloudinary account

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SiddhantVgaikwad/TwitterClone.git
   ```

2. **Configure environment variables**
   Create a `.env` file in both `client/` and `server/`:
   ```
   MONGO_URI=your_mongodb_connection  
   JWT_SECRET=your_jwt_secret  
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   ```

3. **Install dependencies and start the app**
   ```bash
   cd client && npm install && npm start
   cd ../server && npm install && npm run dev
   ```

---

## 📸 Feature Showcase


---

## 🤝 Contributing

We welcome contributions!  

1. **Fork the repo**  
2. **Create a new branch**
   ```bash
   git checkout -b feat/your-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m "feat: add awesome feature"
   ```
4. **Push and create a Pull Request**

---

## 📄 License
MIT © [Siddhant Gaikwad](https://github.com/SiddhantVgaikwad)

---

## 👨‍💻 Crafted with ❤️ by Siddhant Gaikwad  
*Full Stack Developer*

[LinkedIn](#) • [Twitter](#)

---

## 🗣️ Project Explained in My Words (Simple English)

### What is TwitterClone?
This is a small version of Twitter I built using the MERN stack (MongoDB, Express, React, Node). It lets users post tweets, follow others, chat in real-time, and get notifications—just like the real Twitter app.

I added login with JWT (a safe way to keep users logged in), media uploads, light/dark mode, and live notifications using Socket.IO.

### Key Features in Simple Words:
- **Login/Register system** — Users can sign up, login, and even reset their password if they forget it.
- **Make tweets** — You can post tweets with emojis, pictures, or videos.
- **Search tweets** — You can search tweets by hashtags, names, or dates.
- **Real-time messaging** — Chat with people instantly, like WhatsApp.
- **Notifications** — Get alerts when someone likes, retweets, follows, or mentions you.
- **Dark & Light mode** — Switch between themes.
- **Tweet threads & bookmarks** — Group replies like a thread, and save tweets for later.
- **Tweet analytics** — Verified users can see how well their tweets are doing.

---



### ⭐ JWT Authentication
- **Situation**: Needed a secure way to keep users logged in.
- **Task**: Set up a system for sign up, login, logout, and token-based security.
- **Action**: Implemented JWT in the backend with refresh tokens and middleware for route protection.
- **Result**: Created a secure auth system that handles login/logout smoothly without exposing user data.

### ⭐ Real-Time Messaging
- **Situation**: Wanted to make chatting feel instant, like real social apps.
- **Task**: Add a real-time direct messaging system.
- **Action**: Integrated Socket.IO on both frontend and backend for live chat.
- **Result**: Users can now chat instantly with each other with no page refresh.

### ⭐ Tweet System with Media
- **Situation**: Users needed a way to express themselves more than just text.
- **Task**: Add support for emojis, images, videos in tweets.
- **Action**: Used Cloudinary for media uploads and emoji pickers in the tweet composer.
- **Result**: Users can now tweet with rich content, improving engagement.

### ⭐ Notifications
- **Situation**: Needed to keep users updated on activities like likes or retweets.
- **Task**: Build a push notification system.
- **Action**: Used Socket.IO and MongoDB triggers to send notifications in real-time.
- **Result**: Users get instant updates, which improves interaction and time on site.

### ⭐ Search & Filters
- **Situation**: Wanted users to find specific tweets quickly.
- **Task**: Add a smart search bar with filters.
- **Action**: Used MongoDB text indexing and built custom filters (hashtags, dates, mentions).
- **Result**: Users can now find tweets quickly and accurately.
