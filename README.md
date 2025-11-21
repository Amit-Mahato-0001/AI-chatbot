# AI Chatbot

[![Repo Size](https://img.shields.io/github/repo-size/Amit-Mahato-0001/AI-chatbot)](https://github.com/Amit-Mahato-0001/AI-chatbot)  
[![License: MIT](https://img.shields.io/github/license/Amit-Mahato-0001/AI-chatbot)](https://github.com/Amit-Mahato-0001/AI-chatbot/blob/main/LICENSE)  

Real-time AI chatbot built with **React** on the frontend and **Node.js / Express / Socket.io** on the backend, using **Google GenAI (Gemini 2.0 Flash)** for smart AI responses.

---

## 🚀 Features

- Bi-directional real-time chat with **Socket.io**  
- AI-powered responses via **Google GenAI (gemini-2.0-flash)** model  
- Maintains conversation history to provide contextual replies  
- Easy-to-deploy backend and lightweight React frontend  
- CORS enabled, dotenv configuration, clean folder structure  

---

## 📂 Project Structure

AI-chatbot/
├── backend/
│ ├── src/
│ │ ├── app.js
│ │ └── service/
│ │ └── ai.service.js
│ ├── server.js
│ ├── package.json
│ └── .env
└── frontend/
├── src/
│ └── components/
├── public/
├── package.json
└── vite.config.js


---

## 🔧 Prerequisites

- Node.js (v16+ recommended)  
- npm or yarn  
- Google Cloud account / API key for GenAI (Gemini)  
- `.env` file (see config below)  

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Amit-Mahato-0001/AI-chatbot.git
cd AI-chatbot

2. Backend Setup
cd backend
npm install


Create a .env file inside backend/:

GOOGLE_API_KEY=your_google_genai_api_key_here
PORT=3000
# (Add other environment variables if required)


Start the backend server:

npm start

3. Frontend Setup
cd ../frontend
npm install
npm run dev
