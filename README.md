# Live Link - [Netflix Clone 🎥🍿](https://netflix-clone-production-636d.up.railway.app/)

---

# Netflix Clone (MERN Stack Full-Stack App)

This is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that replicates the core functionalities of Netflix. It features **user authentication**, **movie browsing**, **video streaming UI**, **search feature** and a **watch history system**.

This project demonstrates a seamless integration of frontend and backend technologies to build a robust streaming service-like experience, with full responsiveness and secure user flows.

---

## Features & Highlights : 

1) **Movies & Series Sections 🎬📺:** The homepage is divided into two separate sections—one for Movies and another for Series, making it easy to browse by category.
   
2) **Search Functionality 🔎:** A powerful search bar allows users to search for movies, series, or actors by name.
   
3) **Search History 🕵️:** The app tracks and stores a search history, so users can easily revisit previously watched or searched content.
 
4) **Detailed Movie Page 📝🎞:** Clicking on a title shows in-depth info, the trailer, and a carousel of similar recommendations based on that content.

5) **User Authentication 🔐:** Secure registration and login system with JWT-based authentication.

6) **Responsive Design 📱💻:** This website is highly responsive and works well on all screen sizes. 

7) **Streaming UI 🍿:** Designed to replicate the Netflix user experience with hover effects, trailer previews, and category sliders.

8) **MongoDB Integration 🍃:** All user data and preferences are stored persistently using MongoDB Atlas and Mongoose.

9) **Protected Routes 🛡:** Authenticated routes ensure that only logged-in users can access personal content like the dashboard or watchlist.

---

## Technologies Used 🛠️

![My Skills](https://skillicons.dev/icons?i=mongodb,express,react,nodejs,js,html,css,tailwind)

- **MongoDB**: NoSQL database for storing user and video data.
- **Express.js**: Backend framework for handling API routes and middleware.
- **React.js**: Frontend library for building dynamic UIs.
- **Node.js**: JavaScript runtime for building the backend server.
- **JWT (jsonwebtoken)**: Used for user authentication.
- **Axios**: For making HTTP requests from the frontend.
- **TailwindCSS**: For fast, utility-based styling.
- **React Router**: For client-side routing and navigation.
- **Context API / Redux**: For state management.

---

## Pages

### 1. **Landing / Home Page** 🏠  
   - Browse categories, featured titles, and trending picks.
   - Responsive grid layout with movie posters and hover previews.

### 2. **Auth Pages** 🔑  
   - Login and Signup pages with validation.
   - JWT is stored in localStorage and used for protected routes.

### 3. **Movie Details Page** 📽  
   - Click a title to view detailed info, trailer, and a description.

### 4. **User Dashboard / Watchlist** 📋  
   - View saved shows and easily remove titles from the watchlist.

---

## Screenshots & Demo 📸

### 💻 Desktop View

[<img src="https://your-demo-screenshot-url.com/desktop.png" width="320">](https://your-demo-link.com)

### 📱 Mobile View

[<img src="https://your-demo-screenshot-url.com/mobile.png" width="220">](https://your-demo-link.com)

---


## Installation & Setup 🧰

### 1. Clone the repository

```bash
git clone https://github.com/your-username/netflix-clone.git
cd netflix-clone
```

### 2. Install dependencies

#### For the **frontend**:

```bash
cd client
npm install
```

#### For the **backend**:

```bash
cd server
npm install
```

### 3. Environment Variables

Create `.env` files in both `client` and `server` folders as needed.

#### Example `.env` for backend:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

### 4. Run the app

Start both servers:

```bash
# Start backend
cd server
npm start

# Start frontend (in another terminal)
cd client
npm start
```

---

## Contributing 🤝

All contributions are welcome! If you'd like to add features or fix bugs:

1. Fork the repo
2. Create a new branch (`git checkout -b feature-name`)
3. Make your changes
4. Commit your changes
5. Push to your fork (`git push origin feature-name`)
6. Submit a pull request

---

## License 📄

MIT License  
© 2025 [Your Name]

---

Want me to generate this as a real markdown file you can drop into your repo? Or maybe help create badges and deploy instructions with Vercel/Render for full-stack hosting?
