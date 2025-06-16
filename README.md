# MERN - To-Do List App built with the MERN stack using Next.js
A full-stack **To-Do List app** built using **MongoDB, Express, Node.js**, and **Next.js** (React Framework) for the frontend.
---

## 🛠 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/)
- **Backend API**: [Express.js](https://expressjs.com/)
- **Database**: [MongoDB](https://www.mongodb.com/)
- **HTTP Client**: [Axios](https://axios-http.com/)
- **Styling**: Tailwind CSS / CSS Modules (optional)

---

## 📁 Project Structure
mern-todo-nextjs/
├── Server/
│ ├── models/
│ ├── routes/
│ └── server.js
└── todo-next.js/
├── src/
│ ├── page.tsx
│ └── api/
├── components/
└── utils/


## 🚀 Features

- ✅ Add new tasks
- 📋 View all tasks
- ✔️ Mark tasks as completed
- ❌ Delete tasks
- 💡 Simple & clean UI with Next.js SSR/CSR


### 🔹 1. Clone Repo
git clone https://github.com/yourusername/mern-todo-nextjs.git
cd mern-todo-nextjs

🔹 2. Setup Backend
cd Server
npm install
Create .env file:
PORT=5000
MONGO_URI=your_mongodb_uri

Run backend server:
npm start

🔹 3. Setup Frontend
cd ../todo-nextjs
npm install
npm run dev

Visit: http://localhost:3000
🔌 API Endpoints (Express)
| Method     | Endpoint      | Description       |
| ---------- | ------------- | ----------------- |
| **GET**    | `/get`        | Get all todos     |
| **POST**   | `/add`        | Add a new todo    |
| **PUT**    | `/update/:id` | Mark todo as done |
| **DELETE** | `/delete/:id` | Delete a todo     |

