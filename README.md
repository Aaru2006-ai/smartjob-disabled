# SmartJob-Disabled — Prototype Job Portal for Disabled People

This repository contains a working prototype of an accessible job portal focused on people with disabilities. It includes a web frontend (React) and a Node.js backend using SQLite for storage. Voice navigation and voice-assisted forms are implemented with the Web Speech API.

Run locally
1. Server
   - cd server
   - npm install
   - npm start
   - Server will run at http://localhost:4000

2. Client (development)
   - cd client
   - npm install
   - npm run dev
   - Client dev server will run (Vite) typically at http://localhost:5173

Notes
- The server initializes the SQLite database from migrations/init.sql on first run.
- The SpeechRecognition Web API works best in Chrome/Edge. Allow microphone access.

Security note
- This is a demo. Replace secrets and use production-grade DB/config for production deployments.
