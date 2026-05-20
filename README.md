 AI Meeting Summarizer

AI-powered meeting summarization platform built with React, FastAPI, MongoDB, and Gemini AI. The application converts lengthy meetings into concise summaries, extracts action items, identifies key discussion points, and generates intelligent meeting insights through a modern SaaS-style interface.

---

 Features

* AI-generated meeting summaries
* Action item extraction
* Key discussion point detection
* Speech-to-text meeting transcription
* Upload meeting transcripts and audio files
* JWT authentication system
* Meeting history dashboard
* PDF export support
* Responsive modern UI
* Dark/light mode support
* Real-time AI processing

---

 Tech Stack

 Frontend

* React
* Tailwind CSS
* Vite
 Backend

* FastAPI
* Python

 Database

* MongoDB
 AI Integration

* Gemini API

---
 Folder Structure

```bash
project/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── services/
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── utils/
│
├── README.md
└── .gitignore
```

---
 Installation & Setup

Clone Repository

```bash
git clone https://github.com/yourusername/ai-meeting-summarizer.git
cd ai-meeting-summarizer
```

---
Backend Setup

```bash
cd backend
npm install
```

Create `.env` file inside backend:

```env
MONGO_URI=your_mongodb_uri
PORT=5000
JWT_SECRET=your_secret
JWT_REFRESH_SECRET=your_refresh_secret
GEMINI_API_KEY=your_api_key
```

Run backend:

```bash
npm run dev
```

---
 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

Backend runs on:

```bash
http://localhost:5000
```

---
 Future Enhancements

* Real-time meeting assistant
* Team collaboration
* Multi-language support
* AI sentiment analysis
* Calendar integrations
* Voice-based AI assistant

---
 Use Cases

* Team meetings
* Online lectures
* Business discussions
* Interview summaries
* Productivity management

---
 Project Goal

This project was developed as a portfolio-grade AI SaaS application showcasing:

* Full-stack development
* AI integration
* REST API development
* Authentication systems
* Database management
* Modern responsive UI/UX

--- 

This project is intended for educational, portfolio, and research purposes.

