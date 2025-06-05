# ERP-PROJECT
A complete **ERP (Enterprise Resource Planning)** web application for college automation, built with a modern **MERN-style stack**.

This project handles:
-  User management
-  Request handling
-  Cloud image upload (Cloudinary)
-  Email OTP sending
-  JWT-based authentication
-  Fully responsive frontend using **Tailwind CSS**

## 📁 Project Structure
.
├── Frontend/       # Vite + Tailwind CSS frontend
└── Backend/        # Node.js + Express + MongoDB backend

Tech Stack
🖥 Frontend
Vite

Tailwind CSS

JavaScript

⚙️ Backend
Node.js

Express.js

MongoDB (Mongoose)

JWT for Auth

Nodemailer (for emails)

Cloudinary (image uploads)

Prerequisites
Node.js (v16+)

npm

MongoDB Atlas account

Vercel or any frontend host (Netlify, Firebase Hosting)

⚙️ Setup Instructions
>> Environment Variables (.env for Backend)
PORT = 8000
MONGODB_URI = <your-mongodb-uri>
CORS_ORIGIN = *

ACCESS_TOKEN_SECRET = <your-secret>
ACCESS_TOKEN_EXPIRY = 1d
REFRESH_TOKEN_SECRET = <your-secret>
REFRESH_TOKEN_EXPIRY = 10d

# Cloudinary
CLOUDINARY_CLOUD_NAME = <your-cloud-name>
CLOUDINARY_API_KEY = <your-api-key>
CLOUDINARY_API_SECRET = <your-api-secret>

# Email OTP
MAIL_HOST = smtp.gmail.com
MAIL_USER = <your-email>
MAIL_PASSWORD = <your-app-password>

🖥 Running Frontend
cd Frontend
npm install
npm run dev

🗄 Running Backend
cd Backend
npm install
npm run dev
Runs at: http://localhost:8000

📜 Scripts
Backend (package.json)
"scripts": {
  "dev": "nodemon -r dotenv/config --experimental-json-modules src/index.js"
}


