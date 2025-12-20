# Thinkboard
  
 A full-stack note-taking app with a RESTful API.

---

## Features
-  CRUD operations for the note data
-  Responsive UI built with React
-  RESTful API with Express
-  Database integration (MongoDB)

---

## Tech Stack
**Frontend:** React + Vite + TailwindCSS  
**Backend:** Node.js + Express  
**Database:** MongoDB (Mongoose)  
**Other:** Axios

---

## Gif

![ezgif-3232acf975d19c](https://github.com/user-attachments/assets/bbfc35a7-66d6-4d6a-ae5c-56564500066d)
---

## Setup

1. **Clone Repository**
   ```bash
   git clone https://github.com/baranoner/thinkboard.git
   cd thinkboard
2. **Install Dependencies**
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
3. **.env Setup**

Create a file with .env extension in backend (`/backend`)
```
MONGO_URI=<your_mongo_uri>

UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>

NODE_ENV=development
``` 

## 🔧 Run the Backend

```
cd backend
npm run dev
```
Backend -> http://localhost:5001
## Run the Frontend

```
cd frontend
npm run dev
```
Frontend -> http://localhost:5173
