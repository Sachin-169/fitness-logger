# 🏋️ Fitness Logger

## 📌 Description
Developed a full-stack web application to track exercises, maintain streaks, and visualize fitness progress through interactive graphs. The platform helps users stay consistent and motivated by setting achievable goals and monitoring daily performance.

---

## 🚀 Tech Stack
- **Frontend:** React.js, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Other:** REST APIs  

---

## ✨ Features
- 🔐 User authentication using college credentials (PESU login system)
- ➕ Add, edit, and delete exercises  
- 🔥 Track exercise streaks and daily summaries  
- 📊 Interactive progress graphs for visualization  
- 🎯 Set and monitor fitness goals  
- ⚡ Smooth backend integration using REST APIs  

---

## 🧠 Learning Outcomes
- Gained hands-on experience in full-stack development using the MERN stack  
- Built and integrated REST APIs for efficient data handling  
- Implemented user authentication and protected routes  
- Learned best practices in state management and responsive UI design  




2. Backend Setup
cd server
npm init -y
npm install express cors dotenv cookie-parser jsonwebtoken mongodb axios nodemon


Create a .env file in the server/ directory:

PORT=4000
MONGO_URI=mongodb://localhost:27017/fitness_logger
JWT_SECRET=replace_with_a_strong_secret
PESU_AUTH_URL=https://pesu-auth.onrender.com
CLIENT_ORIGIN=http://localhost:5173
NODE_ENV=development


✅ Start backend:

npm run dev
