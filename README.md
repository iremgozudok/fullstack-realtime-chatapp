## Live Demo

- Deployed App: [fullstack-realtime-chatapp](https://fullstack-realtime-chatapp-nciz4.sevalla.app/)

## Overview
A full‑stack real‑time chat application featuring authentication, 1:1 messaging, online user presence, image upload for avatars, and instant notifications. Built with a modern React/Vite frontend and a Node.js/Express backend powered by MongoDB and Socket.IO.

## Features
- Real‑time messaging with Socket.IO
- Secure auth with JWT (HTTP‑only cookies)
- User signup/login/logout
- Update profile picture (Cloudinary upload)
- Online users presence broadcasting
- Responsive UI with Tailwind CSS + DaisyUI
- Production build served by the backend in production

## Tech Stack
- Frontend:
  - React 19, React Router 7, Vite 7
  - Tailwind CSS, DaisyUI
  - Zustand (state management)
  - Axios, react-hot-toast, lucide-react
  - socket.io-client
- Backend:
  - Node.js, Express
  - MongoDB with Mongoose
  - JWT (jsonwebtoken), bcryptjs
  - Cookie Parser, CORS, dotenv
  - Socket.IO server
  - Cloudinary (media storage)
  - Resend (transactional emails)
  - Arcjet (bot/abuse protection)