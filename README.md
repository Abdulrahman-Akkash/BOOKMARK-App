# 🔖 Bookmark App

A full-stack web application that allows users to save, manage, and access bookmarks efficiently.  
Built with **Ruby on Rails (API)** on the backend and **React** on the frontend.

---

## 🚀 Features

- ✨ User-friendly interface to add and manage bookmarks
- 🔗 RESTful API built with Ruby on Rails
- 🧭 Frontend built with React + modern JavaScript
- 🧩 Persistent storage with SQLite / PostgreSQL
- 🧠 Modular design for future extension (authentication, tagging, search, etc.)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Abdulrahman-Akkash/BOOKMARK-App.git
cd bookmark_app

Backend Setup (Rails API)
cd bookmark_api
bundle install
rails db:create db:migrate
rails s -p 3001
This will start the backend API at http://localhost:3001

3️⃣ Frontend Setup (React)

Open a new terminal:

cd ../bookmark-frontend
npm install
npm start


Frontend runs on http://localhost:5473

Environment Variables

Create a .env file inside the frontend and backend folders.

Example for frontend (bookmark-frontend/.env):

REACT_APP_API_URL=http://localhost:3001

🧪 Testing

Backend:

cd bookmark_api
rails test


Frontend:

cd bookmark-frontend
npm test

📦 Deployment

Backend can be deployed to Render, Railway, or Heroku.

Frontend can be deployed to Vercel or Netlify.

Make sure the environment variables are correctly configured in both.

👨‍💻 Tech Stack
Layer	Technology
Frontend	React, Axios
Backend	Ruby on Rails (API mode)
Database	PostgreSQL
Styling	Tailwind / CSS Modules
Version Control	Git + GitHub

🧑‍🎓 Author

Abdulrahman Akkash
💼 GitHub: @Abdulrahman-Akkash
```

🏁 Quick Start Summary

# Clone repo

git clone https://github.com/Abdulrahman-Akkash/BOOKMARK-App.git
cd bookmark_app

# Run backend

cd bookmark_api
bundle install
rails db:create db:migrate
rails s -p 3001

# Run frontend

cd ../bookmark-frontend
npm install
npm start

App will be available at:
Frontend: http://localhost:5473

Backend: http://localhost:3001
