Mind Heal - MERN Stack 🧠💻

A full-featured online physiotherapy web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). This platform allows physiotherapists to conduct online sessions while enabling patients to book, attend, and track therapy appointments from anywhere.

🔹 Features

For Patients 🧍‍♂️🧍‍♀️

✅ User Authentication (Sign up/Login)

✅ Browse available therapy sessions

✅ Book therapy sessions online

✅ View and manage therapy history

✅ Interact with physiotherapists

For Physiotherapists 👨‍⚕️👩‍⚕️

✅ Physiotherapist Authentication (Sign up/Login)

✅ Post and manage training sessions

✅ View patient bookings and feedback

✅ Update therapy details and materials

✅ Monitor patient progress

General Features

✅ Secure authentication with JWT & cookies

✅ Persistent login with Redux-Persist

✅ Global state management using Redux Toolkit

✅ Responsive UI with Tailwind CSS

✅ Toast notifications for feedback

✅ Dynamic routing with React Router

🔹 Tech Stack

Frontend: React.js, Redux Toolkit, React Router, Tailwind CSS

Backend: Node.js, Express.js, MongoDB, Mongoose

Authentication: JWT (JSON Web Tokens), Cookies

State Management: Redux Toolkit

API Calls: Axios

UI Components: ShadCN UI, Lucide-React Icons

🔹 How to Run the Project

👉 Clone the repository

git clone https://github.com/your-username/mind-heal.git
cd mind-heal

👉 Set up the backend

cd backend
npm install

Create a .env file in the backend folder and add:

PORT=5000
MONGO_URI=mongodb://localhost:27017/mindheal
JWT_SECRET=your_jwt_secret

npm start

👉 Set up the frontend

cd ../frontend
npm install
npm start

👉 Visit the application

http://localhost:3000
