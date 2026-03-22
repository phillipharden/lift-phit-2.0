# 🏗 Architecture

## 🧱 Tech Stack

### Frontend
- React (Vite)
- React Router
- CSS (custom / utility-based)

### Backend
- Node.js
- Express.js

### Database
- MongoDB (Mongoose)

---

## 🔄 Application Flow

1. User logs in
2. Frontend requests workout data
3. Backend processes request
4. Database returns user/workout data
5. Frontend renders workout UI

---

## 📡 Data Flow

Client → API → Controller → Database → Response → UI

---

## 🗂 Project Structure
client/
├── components/
├── pages/
├── routes/
└── services/

server/
├── models/
├── controllers/
├── routes/
└── middleware/


---

## 🔐 Authentication (Planned)

- JWT-based authentication
- Protected routes
- User-specific data

---

## ⚡ Performance Goals

- Fast load times (Vite)
- Minimal API calls
- Efficient state updates

