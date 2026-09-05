# 🌍 OneLearn

> **One Classroom. Every Learner.**

OneLearn is an AI-powered accessibility platform for inclusive classrooms. It helps students with different accessibility needs learn from the same teacher and lesson in real time.

## 🚨 Problem

Traditional classrooms follow a one-size-fits-all approach, creating barriers for students with hearing, visual, communication, and reading difficulties.

## 💡 Solution

OneLearn adapts the classroom experience to each learner.

| Need | Support |
|---|---|
| 🦻 Deaf / Hard-of-Hearing | Live Captions + ISL |
| 👁️ Low Vision | AI Image/Board Description + Audio |
| 🗣️ Non-speaking | AAC Communication |
| 📖 Reading Difficulty | Simplify-This |

## ✨ Features

- 🎙️ Real-time Speech-to-Text
- 🤟 ISL 3D Avatar
- 👁️ AI Board & Image Understanding
- 📖 Simplify-This
- 🗣️ AAC Communication
- 🏫 Physical Classroom Mode
- 💻 Remote / Live Classroom with WebRTC
- 📡 Real-time WebSocket Communication
- 🔐 JWT Authentication

## 🛠️ Tech Stack

**Frontend:** Next.js, React, TypeScript, Tailwind CSS, WebRTC, Three.js

**Backend:** Python, FastAPI, Uvicorn, SQLAlchemy, Pydantic, WebSockets

**Database:** SQLite

**AI:** Groq Whisper, Google Gemini Vision, Browser TTS

## 🏗️ Architecture

```text
Teacher
   ↓
Speech / Board / Input
   ↓
FastAPI Backend
   ↓
WebSocket
   ↓
Captions + ISL + AAC
   ↓
```

## 🚀 Run Locally

### Backend
...
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
Frontend
cd frontend
npm install
npm run dev

Frontend: http://localhost:3000

Backend: http://localhost:8000

🎯 Vision

We don't create a different classroom for different students. We create one classroom that works for everyone.

OneLearn

One Classroom. Every Learner.


Ye version **GitHub README ke liye clean bhi hai aur unnecessarily lengthy bhi nahi hai.**
