🚀 Job Portal Application

A full-stack Job Portal web application built using React, Redux Toolkit, Node.js, Express, and MongoDB.
It allows users to register, login, browse jobs, apply with a cover letter, and view applied jobs.
Admins can create, edit, and delete job listings.

🛠️ Tech Stack
Frontend
React.js
Redux Toolkit
React Router
Axios
Tailwind CSS
Backend
Node.js
Express.js
MongoDB Atlas
Mongoose
JWT Authentication
Bcrypt


📦 Features
👤 User
Signup & Login
View all jobs
Apply to jobs with cover letter
View applied jobs

🛠️ Admin
Create jobs
Edit jobs
Delete jobs

🎨 UI Features
Responsive UI
Dark mode
Toast notifications
Loading states

⚙️ Setup Instructions
1️⃣ Clone Repository
git clone https://github.com/YOUR_USERNAME/job-app.git
cd job-app

2️⃣ Backend Setup
cd backend
npm install
Create .env file:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=mysupersecret
Run backend:
npm run dev

3️⃣ Frontend Setup
cd frontend
npm install
npm start

💻 Run Locally
Service	URL
Frontend	http://localhost:3000
Backend	http://localhost:5000

🔐 Environment Variables
Backend (.env)
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key

📁 Project Structure
job-app/
│
├── backend/
│   ├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── index.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── features/
│   └── app/


🧪 API Endpoints
Auth
POST /api/auth/signup
POST /api/auth/login
Jobs
GET /api/jobs
POST /api/jobs (Admin)
PUT /api/jobs/ (Admin)
DELETE /api/jobs/ (Admin)
Applications
POST /api/jobs//apply
GET /api/jobs/applied
