
📚 E-Learning Platform
A full-stack E-learning Web Application built with React (Vite) on the frontend, Node.js + Express on the backend, MongoDB for the database, and deployed via Vercel.

🚀 Live Demo
# WEBSITE LINK
**https://e-learning-six-iota.vercel.app/**

📁 Project Structure

e-learning-app/
├── backend/          # Node.js + Express API server
├── frontend/         # React + Vite client
├── package.json      # Root package.json with monorepo scripts
└── README.md         # Project documentation


⚙️ Quick Start
1. Install Dependencies

npm run install:all
Installs dependencies for the root, backend, and frontend.

2. Run Development Servers

npm run dev
Starts both:

🔙 Backend: Express server with Nodemon (usually at http://localhost:9000)

🔜 Frontend: Vite dev server (usually at http://localhost:5173)

📦 Root-Level Scripts
Run these from the root folder:

Command	Description
npm run dev	Start both frontend and backend in dev mode
npm run start	Start both in production mode
npm run install:all	Install all dependencies
npm run build	Build frontend for production
npm run backend	Start backend only
npm run frontend	Start frontend only

🧩 Individual Project Commands
🔙 Backend (/backend)
Command	Description
npm run dev	Start development server with Nodemon
npm start	Start backend in production

🔜 Frontend (/frontend)
Command	Description
npm run dev	Start Vite dev server
npm run build	Build production bundle
npm run preview	Preview production build locally

🛠️ Required Dependencies
Make sure to install these in respective directories:

Backend (/backend)

npm install express mongoose cors dotenv jsonwebtoken bcryptjs nodemon
Frontend (/frontend)

npm install react react-dom react-router-dom axios
Dev Tools (optional):


npm install -D nodemon concurrently
✨ Features
Frontend: React (Vite) + JavaScript + Tailwind CSS

Backend: Node.js + Express + JWT Auth

Database: MongoDB with Mongoose

Authentication: Register/Login with JWT

Courses: Browse, Enroll, and Manage E-learning content

Responsive: Fully responsive UI for all devices

🌐 Deployment
Frontend deployed on Vercel. You can link your GitHub repo directly to Vercel for CI/CD.

For backend (optional):
You can deploy to Render, Railway, or MongoDB Atlas + Vercel serverless functions.

🔐 Environment Variables
Create a .env file inside /backend:


PORT=9000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
🧪 Development Steps



cd e-learning-app
Install dependencies
npm run install:all
Add your .env in /backend

Start development servers:

npm run dev
Open browser at http://localhost:5173



