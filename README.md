AI Chatbot

Real-time AI chatbot built with React on the frontend and Node.js / Express / Socket.io on the backend, using Google GenAI (Gemini 2.0 Flash) for AI responses.

🚀 Features

• Real-time bi-directional chat using Socket.io
• Smart replies using Google GenAI (gemini-2.0-flash)
• Maintains full chat history for contextual answers
• Clean frontend + backend folder structure
• dotenv + CORS enabled
• Easy to extend and deploy

📂 Project Structure

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

🔧 Prerequisites

• Node.js v16+
• npm or yarn
• Google GenAI API Key (Gemini)
• .env file inside backend/

⚙️ Setup & Installation

Clone repository
git clone https://github.com/Amit-Mahato-0001/AI-chatbot.git

cd AI-chatbot

Backend setup
cd backend
npm install

Create .env file inside backend/:
GOOGLE_API_KEY=your_api_key_here
PORT=3000

Start backend:
npm start

Frontend setup
cd ../frontend
npm install
npm run dev

Frontend URL: http://localhost:5173

Backend URL: http://localhost:3000
