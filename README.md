# AI Chatbot

**Real-time** AI chatbot using **React** (frontend) and **Node.js / Express / Socket.io** (backend), powered by **Google GenAI (Gemini 2.0 Flash)**.

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Project Structure](#project-structure)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Configuration](#configuration) 

---

## Features

- Real-time chat with **Socket.io**  
- Conversational AI responses via **Gemini 2.0 Flash**  
- Maintains chat history for context-aware replies  
- Clean and modular code structure  
- Environment variables support with `dotenv`  
- CORS enabled for secure cross-origin communication  

---

## Tech Stack

- **Frontend:** React, Vite  
- **Backend:** Node.js, Express, Socket.io  
- **AI:** Google GenAI (`@google/genai`)  
- **Other:** dotenv, CORS  

---

## Project Structure

AI-chatbot/  
├── backend/  
│   ├── src/  
│   │   ├── app.js  
│   │   └── service/  
│   │       └── ai.service.js  
│   ├── server.js  
│   ├── package.json  
│   └── .env  
└── frontend/  
    ├── src/  
    │   └── components/  
    ├── public/  
    ├── package.json  
    └── vite.config.js  

---

## Prerequisites

- Node.js (recommend v16+)  
- npm ya yarn  
- Google GenAI API Key (Gemini)  
- Internet connection (For AI)  

---

## Installation

1. Clone karo repo:  
   `git clone https://github.com/Amit-Mahato-0001/AI-chatbot.git`  
   `cd AI-chatbot`  

2. Backend setup:  
   `cd backend`  
   `npm install`  

3. Frontend setup:  
   `cd ../frontend`  
   `npm install`  
   `npm run dev`  

---

## Configuration

Create a `.env` file in backend and set this variables :

GOOGLE_API_KEY=your_google_genai_api_key_here
PORT=3000


