<h1 align="center">MERN Netflix Clone 🎬</h1>

A full-stack **Netflix Clone** web application that allows users to sign up, log in, and explore trending movies and TV shows, watch trailers, and manage search history — all powered by **The Movie Database (TMDB)** API.

This project replicates Netflix’s core functionality and user experience using **React (Vite)** on the frontend and **Node.js + Express + MongoDB** on the backend with secure **JWT authentication**.

---

![Demo App](/frontend/public/screenshot-for-readme.png)


## 🚀 Features

### 🔐 Authentication
- User **Sign Up / Login / Logout**
- Passwords securely hashed using **bcryptjs**
- Authenticated routes protected using **JWT (JSON Web Token)** stored in **HTTP-only cookies**

### 🎥 Movie & TV Content
- Fetches **trending**, **category-based**, and **similar** movies/TV shows from the **TMDB API**
- View **trailers** directly on the Watch page (via YouTube)
- Responsive movie sliders with smooth navigation

### 🔍 Search & History
- Search for **movies**, **TV shows**, or **actors**
- Personalized **search history** saved per user
- Delete specific history items anytime

### 🖥️ UI/UX
- Netflix-like modern dark theme using **Tailwind CSS**
- Interactive and responsive layout
- Clean mobile navigation with a collapsible menu
- Loading skeletons and shimmer effects for better UX

---

## 🏗️ Tech Stack

| Layer | Technologies |
|--------|--------------|
| **Frontend** | React (Vite), Tailwind CSS, Zustand (state management), React Router, Axios |
| **Backend** | Node.js, Express.js, MongoDB, Mongoose, JWT, bcryptjs, cookie-parser |
| **API Source** | [TMDB (The Movie Database)](https://www.themoviedb.org/documentation/api) |
| **Others** | Lucide React Icons, React Player, Toast Notifications |

---


I wanted to build a full-stack application that mimics Netflix to enhance my MERN stack skills and understand API integration in real-world scenarios. The idea was to let users explore, search, and watch trailers of trending movies and shows.
My task was to design and implement a complete Netflix-like web app with secure authentication, TMDB API integration, and an elegant, responsive UI similar to Netflix.
I developed a RESTful backend using Node.js, Express, MongoDB, and JWT for authentication and user management.
I integrated TMDB API to fetch trending and categorized movies and TV shows, built a React + Tailwind frontend with Zustand for state management, and implemented dynamic search and watch pages using React Router and ReactPlayer.
The final app allows users to securely log in, explore movies and shows, view trailers, and manage their search history — replicating Netflix’s experience.
This project strengthened my expertise in MERN stack development, REST API integration, and frontend UI/UX optimization.

### Setup .env file

PORT=5000
MONGO_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secre
TMDB_API_KEY=your_tmdb_api_key
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
