# Full-Stack MERN Application

This project is a **full-stack web application** consisting of a **React frontend** and an **Express.js + MongoDB backend**.  
It follows a modern MERN architecture (MongoDB, Express, React, Node.js) and is structured into two main folders:

- `client/` → React frontend  
- `server/` → Node.js + Express backend  

The app is designed to provide an **interactive, real-time user experience** with secure authentication and efficient API communication.

---

## 🌐 Frontend (`client/`)

The frontend is built using **React 18** and bundled with `react-scripts`.  
It focuses on providing a responsive, smooth, and component-driven UI.

### ✨ Key Features
- **Routing:** Implemented using `react-router-dom v6` for smooth client-side navigation.  
- **Rich Text Editing:** Integrated `react-quill` for user-generated content.  
- **Time Display:** Uses `javascript-time-ago` and `react-time-ago` for user-friendly timestamps.  
- **Icons & UI Enhancements:** `react-icons` provides SVG icons for modern UI.  
- **API Communication:** `axios` for asynchronous HTTP requests to the backend.  
- **Testing:** Configured with `@testing-library/react` for unit and integration tests.  
- **Performance:** `web-vitals` included to monitor and optimize frontend performance.

### 📌 Scripts
npm start      # Run development server
npm run build  # Build optimized production files
npm test       # Run tests
npm run eject  # Eject configuration for advanced customization
🖥️ Backend (server/)
The backend is built using Node.js with the Express.js framework.
It handles API requests, authentication, file handling, and database operations using MongoDB via Mongoose.

🧠 Key Features
Express Framework: Core for routes, middleware, and REST APIs.

MongoDB Integration: Managed with mongoose for schema-based data modeling.

Authentication & Security:

jsonwebtoken for JWT-based authentication

bcryptjs for hashing and verifying passwords

File Uploads: express-fileupload for handling file uploads

CORS: Configured for secure frontend-backend communication

Environment Variables: Managed via dotenv

Unique Identifiers: uuid for generating unique IDs

🧰 Development Dependencies
nodemon automatically restarts the server on code changes

📌 Scripts
bash
Copy code
npm run dev   # Start server
npm run build # Install dependencies (deployment)
🏗️ Project Structure
csharp
Copy code
project-root/
├── client/          # React frontend
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
├── server/          # Express backend
│   ├── index.js
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── package.json
│   └── ...
└── README.md
🚀 Development Workflow
Start Backend
bash
Copy code
cd server
npm install
npm run dev
Start Frontend
Open a new terminal:

bash
Copy code
cd client
npm install
npm start
Visit http://localhost:3000 for the frontend, which communicates with the backend (commonly on http://localhost:5000).

🛠️ Technologies Used
Area	Tech Stack
Frontend	React 18, React Router, Axios, Quill
Backend	Node.js, Express.js, Mongoose
Database	MongoDB
Auth & Security	JWT, bcryptjs
Utilities	UUID, dotenv, nodemon, cors
