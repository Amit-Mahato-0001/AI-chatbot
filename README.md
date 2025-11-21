# AI Chatbot

Real-time AI chatbot built with **React** on the frontend and **Node.js / Express / Socket.io** on the backend, using **Google GenAI (Gemini 2.0 Flash)** for smart AI responses.

---

## 🚀 Features

- Real-time bi-directional chat using **Socket.io**
- AI-powered replies using **Google GenAI (gemini-2.0-flash)**
- Maintains full chat history for better contextual responses
- Lightweight React frontend with clean UI
- Easy-to-deploy backend (Express + Node.js)
- Environment variable support using **dotenv**
- CORS enabled for frontend-backend communication

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

yaml
Copy code

---

## 🔧 Prerequisites

- Node.js (v16+ recommended)
- npm or yarn
- Google Cloud API Key for **Gemini (GenAI)**
- `.env` file inside the backend folder

---

## ⚙️ Setup & Installation

### **1. Clone the Repository**
```bash
git clone https://github.com/Amit-Mahato-0001/AI-chatbot.git
cd AI-chatbot

2. Backend Setup
bash
Copy code
cd backend
npm install
Create a .env file inside backend/:

ini
Copy code
GOOGLE_API_KEY=your_google_genai_api_key_here
PORT=3000
Start the backend server:

bash
Copy code
npm start
3. Frontend Setup
bash
Copy code
cd ../frontend
npm install
npm run dev
Frontend runs on:

arduino
Copy code
http://localhost:5173
Backend runs on:

arduino
Copy code
http://localhost:3000
