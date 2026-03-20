# 💼 Job Portal – Full Stack MERN Application  

[![React](https://img.shields.io/badge/Frontend-React-61DBFB?logo=react&logoColor=white)](https://react.dev/)  
[![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?logo=node.js&logoColor=white)](https://nodejs.org/)  
[![Express](https://img.shields.io/badge/Framework-Express-000000?logo=express&logoColor=white)](https://expressjs.com/)  
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)  
[![Clerk](https://img.shields.io/badge/Auth-Clerk-3E63DD?logo=clerk&logoColor=white)](https://clerk.com/)  
[![Sentry](https://img.shields.io/badge/Monitoring-Sentry-362D59?logo=sentry&logoColor=white)](https://sentry.io/)  
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?logo=vercel&logoColor=white)](https://vercel.com/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

## 📖 Overview  

This project is a **Full Stack Job Portal Website** built with the **MERN stack** (MongoDB, Express, React, Node.js).  

- 👩‍💻 **Job Seekers** can:  
  - Search and apply for job openings  
  - Upload and manage their resume  
  - Authenticate securely via **Clerk**  

- 🏢 **Recruiters** can:  
  - Post and manage job openings  
  - Review applications from candidates  
  - Accept or reject applications  
  - View applicants’ resumes  

- 🛡 **Sentry** is integrated for error tracking, performance monitoring, and MongoDB query optimization.  

- ☁️ The app is deployed on **Vercel** for global scalability.  

---

## ✨ Features  

- 🔐 **Authentication** – Job seekers login/signup with Clerk  
- 📄 **Resume Upload** – Applicants upload resumes to their profile  
- 🔎 **Job Search & Apply** – Find job openings and apply directly  
- 📊 **Recruiter Dashboard** – Manage job posts & applications  
- ✅ **Application Management** – Accept/Reject applicants with one click  
- 📈 **Monitoring** – Track errors & performance with **Sentry**  
- 🌍 **Deployment** – Hosted on **Vercel**  

---

## 🛠️ Tech Stack  

| Layer       | Technology |
|-------------|------------|
| **Frontend** | React.js (Vite or CRA) |
| **Backend**  | Node.js + Express.js |
| **Database** | MongoDB (Atlas or local) |
| **Auth**     | Clerk |
| **Monitoring** | Sentry |
| **Deployment** | Vercel |

---

## ⚙️ Installation  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
3️⃣ Setup environment variables

Create a .env file in server and client:

Server .env:
MONGO_URI=your_mongodb_uri
CLERK_API_KEY=your_clerk_api_key
SENTRY_DSN=your_sentry_dsn
PORT=5000
Client .env:
# Run backend
cd server
npm run dev

# Run frontend
cd ../client
npm start
4️⃣ Run the app
# Run backend
cd server
npm run dev

# Run frontend
cd ../client
npm start
Deployment

Backend: Hosted on Vercel Serverless Functions or Render/Heroku

Frontend: Deployed on Vercel
📌 Roadmap

 Add filtering & advanced search for jobs

 Email notifications for recruiters & applicants

 Resume parsing with AI

 Role-based authentication (Admin Panel)

🤝 Contributing

Contributions are welcome!

Fork this repository

Create your branch (git checkout -b feature/YourFeature)

Commit changes (git commit -m 'Add some feature')

Push to branch (git push origin feature/YourFeature)

Open a Pull Request

📜 License

This project is licensed under the MIT License.


