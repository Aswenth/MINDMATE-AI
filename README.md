🧘‍♀️ Calmspace – Your Personal Sanctuary for Mindfulness 🌿
“Inhale peace, exhale stress.”
Calmspace is your digital companion for achieving tranquility and mental well-being.

🌟 Overview
Calmspace is a full-stack web application designed to promote mental wellness through guided meditations, mood tracking, and community support. Leveraging the power of AI, Calmspace offers personalized experiences to help users navigate their mental health journey.

🚀 Features
🧘‍♂️ Guided Meditations: Access a library of meditations tailored to various needs.
📈 Mood Tracking: Monitor your emotional well-being over time with intuitive graphs.
🧠 AI-Powered Insights: Receive personalized suggestions based on your mood patterns.
📚 Educational Resources: Explore articles and tips curated by mental health experts.
📧 Email Reminders: Stay on track with regular wellness reminders.
🛠️ Tech Stack
Frontend
⚛️ React.js
🎨 Tailwind CSS
Backend
🖥️ Node.js
🚀 Express.js
🤖 Gemini (Generative AI)
Real-Time Communication
🔌 WebSockets
Email Service
📬 Nodemailer
Database & Authentication
🍃 MongoDB
🔐 Firebase
🧩 System Architecture
Calmspace operates on a modular architecture comprising:

Frontend: User interface built with React.js and Tailwind CSS.
Backend: RESTful API developed using Node.js and Express.js.
WebSocket Server: Enables real-time features like live chat.
Email Server: Handles email notifications and reminders.
🛠️ Local Setup Guide
Prerequisites
📦 Node.js and npm installed
🗄️ MongoDB Atlas account
🔐 Firebase project
🔑 Gemini API key from Google AI
Step-by-Step Installation
Clone the Repository
git clone https://github.com/Naganathan194/Calmspace.git
cd Calmspace
Install Dependencies
Backend
cd Backend
npm install
Frontend
cd ../Frontend
npm install
WebSocket Server
cd ../WebSocketServer
npm install
Email Server
cd ../Email-Server
npm install
Configure Environment Variables
Create .env files in each directory (Backend, Frontend, WebSocketServer, Email-Server) based on the provided .env.example files.
Populate them with your credentials and configuration details.
Run the Application
Backend
cd Backend
npm run dev
Frontend
cd ../Frontend
npm start
WebSocket Server
cd ../WebSocketServer
node index.js
Email Server
cd ../Email-Server
npm start
🤝 Contributing
We welcome contributions! To get started:

🍴 Fork the repository
🌿 Create your feature branch: git checkout -b feature/YourFeature
💬 Commit your changes: git commit -m 'Add YourFeature'
🚀 Push to the branch: git push origin feature/YourFeature
📬 Open a pull request
