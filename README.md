# AI-Powered Library Services Chatbot

## Overview
An intelligent chatbot that automates library services such as book search, holds, renewals, recommendations, event registration, research help, and fine reminders. Designed to handle 100,000+ books using ScaleDown optimization.

## Features
- Book search
- Holds & renewals
- AI-based recommendations
- Mood-based recommendations (Creative Feature)
- Smart reminders
- Usage analytics
- Event registration

## ScaleDown Benefits
- 80% catalog compression
- Faster responses
- Reduced librarian workload
- 24/7 access

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: FastAPI (Python)
- Database: SQLite
- AI: NLP, rule-based recommendation

## How to Run
```bash
pip install fastapi uvicorn
cd backend
uvicorn main:app --reload
