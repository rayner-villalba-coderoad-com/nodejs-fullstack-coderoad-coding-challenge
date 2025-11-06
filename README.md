# CodeRoad NodeJS Coding Challenge
## Quick summary
- **server/** — An Express server exposing a small REST API (`/api/items`) and storing data in `db.json` using Node `fs` (no external DB, no `json-server` dependency).
- **client/** — A Vite + React app (very small) that uses `fetch` to call the API. No UI libraries — plain React, plain CSS.

---

## How to run (local)

Open two terminals.

1. Start the backend:

```bash
cd server
npm install
npm run dev
```

Server runs on `http://localhost:4000` (API base: `http://localhost:4000/api`).

2. Start the frontend:

```bash
cd client
npm install
npm run dev
```

Vite dev server will print its URL (usually `http://localhost:5173`). Open it in your browser. The React app talks to the backend via `fetch`.

---
