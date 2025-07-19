
Here’s your **Calmspace** project write-up, rewritten in a clean and professional format—perfect for README.md or documentation purposes:

---

# 🧘‍♀️ Calmspace – Your Personal Sanctuary for Mindfulness 🌿

***“Inhale peace, exhale stress.”***
Calmspace is your digital companion for achieving tranquility and mental well-being.

---

## 🌟 Overview

**Calmspace** is a full-stack web application designed to promote **mental wellness** through guided meditations, mood tracking, and community support. Leveraging the power of **AI**, it offers personalized experiences to help users navigate their mental health journey.

---

## 🚀 Features

* 🧘‍♂️ **Guided Meditations** – Access a library of meditations tailored to various needs.
* 📈 **Mood Tracking** – Monitor your emotional well-being over time with intuitive graphs.
* 🧠 **AI-Powered Insights** – Get personalized suggestions based on your mood patterns.
* 📚 **Educational Resources** – Read articles and tips curated by mental health experts.
* 📧 **Email Reminders** – Stay on track with regular wellness notifications.

---

## 🛠️ Tech Stack

### 🔹 Frontend

* ⚛️ React.js
* 🎨 Tailwind CSS

### 🔹 Backend

* 🖥️ Node.js
* 🚀 Express.js
* 🤖 Gemini (Google Generative AI)

### 🔹 Real-Time Communication

* 🔌 WebSockets

### 🔹 Email Service

* 📬 Nodemailer

### 🔹 Database & Authentication

* 🍃 MongoDB
* 🔐 Firebase

---

## 🧩 System Architecture

The application follows a **modular architecture**:

* **Frontend** – Built with React.js and styled using Tailwind CSS
* **Backend** – RESTful API using Node.js and Express.js
* **WebSocket Server** – Enables real-time communication (e.g., live chat)
* **Email Server** – Sends reminders and notifications

---

## ⚙️ Local Setup Guide

### ✅ Prerequisites

* 📦 Node.js and npm installed
* 🗄️ MongoDB Atlas account
* 🔐 Firebase project set up
* 🔑 Gemini API key from Google AI

---

### 📥 Step-by-Step Installation

#### 1. **Clone the Repository**

```bash
git clone https://github.com/Aswenth/MINDMATE-AI.git
cd Calmspace
```

#### 2. **Install Dependencies**

##### Backend

```bash
cd Backend
npm install
```

##### Frontend

```bash
cd ../Frontend
npm install
```

##### WebSocket Server

```bash
cd ../WebSocketServer
npm install
```

##### Email Server

```bash
cd ../Email-Server
npm install
```

#### 3. **Configure Environment Variables**

* Create `.env` files in each of the following directories:

  * `Backend/`
  * `Frontend/`
  * `WebSocketServer/`
  * `Email-Server/`
* Use the provided `.env.example` files as templates.
* Fill in the necessary credentials and keys (MongoDB URI, Firebase keys, Gemini API key, etc.)

---

### 🧪 Run the Application

#### Start Backend

```bash
cd Backend
npm run dev
```

#### Start Frontend

```bash
cd ../Frontend
npm start
```

#### Start WebSocket Server

```bash
cd ../WebSocketServer
node index.js
```

#### Start Email Server

```bash
cd ../Email-Server
npm start
```

---




