# Quick Chat App

A full-stack real-time chat app with Express, Socket.IO and React.

## Repository structure

- `quick-chat-backend/`: Node.js + Express + Socket.IO backend
- `quick-chat-frontend/`: Vite + React frontend

## Features

- Real-time messaging using Socket.IO (1:1 chat + group chat)
- User auth with JWT and protected routes
- MongoDB/Mongoose models for users, groups, and messages
- REST API endpoints for user/group/message management
- Mobile-friendly React UI with live updates

## Backend setup

1. `cd quick-chat-backend`
2. `npm install`
3. create `.env` containing:
   - `PORT=5000`
   - `MONGO_URI=your-mongo-uri`
   - `JWT_SECRET=your-jwt-secret`
4. `npm start`

## Frontend setup

1. `cd quick-chat-frontend`
2. `npm install`
3. `npm run dev`

## Scripts

- `npm start` (backend server)
- `npm run dev` (frontend dev server)

## Notes

- Add `node_modules` to `.gitignore` in both frontend/backend.
- If you have merged remote data, prefer pull + merge safe strategy, or force push only when needed.
