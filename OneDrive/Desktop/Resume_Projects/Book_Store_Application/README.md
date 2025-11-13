# Book Store Application

![Demo](/img/demo.png)

Simple full-stack Book Store demo: Express backend + React + Vite frontend.

**Overview**
- **Backend:** Node.js + Express, Mongoose models in `backend/models/`.
- **Frontend:** React app built with Vite in `frontend/`.
- **Purpose:** Demo CRUD operations for books (create, read, update, delete).

**Tech stack**
- Node.js, Express
- MongoDB / Mongoose
- React, Vite
- Tailwind CSS (frontend)

**Quick start (development)**
Open two terminals and run the backend and frontend separately.

Backend:
```powershell
cd backend
npm install
npm run dev
```

Frontend:
```powershell
cd frontend
npm install
npm run dev
```

Frontend runs with Vite (follow the terminal output for port). Backend default port is configured in `backend/config.js` (commonly `5555`).

**Project structure (important files)**
- `backend/` — Express API
	- `index.js` — backend entry
	- `config.js` — configuration
	- `models/bookmodel.js` — Mongoose schema for books
	- `routes/booksRoute.js` — books routes
- `frontend/` — Vite + React app
	- `src/` — React source
	- `src/components/` — UI components
	- `src/pages/` — page views (Home, Create, Edit, Show, Delete)
- `img/demo.png` — demo screenshot (referenced above)

**API (example)**
- `GET /books` — list books
- `GET /books/:id` — get a single book
- `POST /books` — create a book
- `PUT /books/:id` — update a book
- `DELETE /books/:id` — delete a book

