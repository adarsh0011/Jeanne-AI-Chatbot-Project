# Jeanne 🤖 — AI Chatbot Assistant

**Jeanne** is a full-stack AI chatbot application designed to deliver natural, intelligent conversations using OpenAI’s GPT. Built with modern tools like React, Node.js, and Vite, Jeanne features a clean interface, chat history, typing animation, role switching, and optional voice support.

Whether you're experimenting with conversational AI or building something production-ready, Jeanne offers a solid foundation to get started.

---

## ✨ Features

- 🔮 **OpenAI Integration** – GPT-based responses with contextual awareness.
- 💬 **Chat History** – Maintains conversation flow for better continuity.
- 🎭 **Role Switching** – Interact with the bot in various assistant personas.
- ⌨️ **Typing Animation** – Smooth typing effect for enhanced user experience.
- 🎙️ **Speech-to-Text & Text-to-Speech** – Optional voice features using Web Speech API.
- ⚙️ **Modern Tech Stack** – Vite + React frontend and Express backend.

---

## 📂 Project Structure

ai-chatbot/ 
├── client/            # Frontend (React + Vite) │  
├── public/ │  
└── src/ │       
├── assets/ │      
├── components/ │      
├── App.jsx │      
└── ... 
├── server/            # Backend (Node.js + Express) │   
├── server.js │  
├── routes/ │   
├── controllers/ │  
└── ...
└── .env               # Environment variables (keep this secure)

---

## 🚀 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/your-username/jeanne-ai-chatbot.git
cd jeanne-ai-chatbot

2. Configure Environment



Create a .env file inside the server/ folder:

OPENAI_API_KEY=your_openai_api_key

3. Install Dependencies



# Frontend
cd client
npm install

# Backend
cd ../server
npm install

4. Run the Application



# Start backend
node server.js

# Start frontend
cd ../client
npm run dev


🔐 Important Notes

Ensure .env is listed in your .gitignore to keep API keys safe.

For deployment, frontend can be hosted on Vercel and backend on Render or similar platforms.


📄 License

This project is licensed under the MIT License.


🤝 Contributions

Open to feedback, issues, and pull requests! Feel free to contribute to improve Jeanne.


🧠 Powered By

OpenAI

React

Node.js

Vite

> Made with 💻 by Diksha
