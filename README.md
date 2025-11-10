# 🧠 LangGraph ChatFlow with Memory Retention System

A conversational AI system built using **LangGraph**, **LangChain**, and **Google Gemini API**.  
This chatbot retains memory between conversations using a custom **SQLite-based memory backend** and a **graph-driven chatflow** for smarter context management.

---

## 🚀 Features

- 🧩 **LangGraph-powered Chatflow** – modular, node-based conversational logic  
- 🧠 **Memory Retention System** – stores and recalls previous chat states using SQLite  
- 🤖 **Google Gemini 2.0 Flash Integration** – used as the core language model  
- 💾 **Database-backed Conversations** – persistent history with `chatbot.db`  
- 🧰 **Simple, Modular Codebase** – split into `backend_db.py` and `frontend_db.py` for clarity  

---

## 🧩 Project Structure

Langgraph-ChatFlow-with-Memory-Retention/
│
├── backend_db.py # Backend logic & LangGraph chatflow configuration
├── frontend_db.py # Frontend / API-side or chat interface
├── chatbot.db # SQLite memory storage (ignored by Git)
├── .env # API keys (ignored by Git)
├── .gitignore # Prevents sensitive files from being uploaded
├── requirements.txt # Python dependencies
└── README.md # Project documentation
