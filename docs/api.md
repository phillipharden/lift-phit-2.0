# 🔌 API Design

## 🌐 External API

Lift-Phit may integrate with:

- https://api-ninjas.com/api/exercises

Used for:
- exercise data
- descriptions
- possible form guidance

---

## 🧩 Internal API (Planned)

### Auth Routes
- POST /api/auth/register
- POST /api/auth/login

---

### Workout Routes
- GET /api/workouts
- POST /api/workouts
- PUT /api/workouts/:id
- DELETE /api/workouts/:id

---

### Exercise Routes
- GET /api/exercises
- POST /api/exercises

---

## 📊 Status Codes

- 200 → Success
- 400 → Bad request
- 401 → Unauthorized
- 404 → Not found
- 500 → Server error

---

## ⚠️ Error Handling

All responses follow:

```json
{
  "success": false,
  "message": "Error message"
}


---

# 📄 docs/frontend.md

```md
# 🎨 Frontend

## ⚛️ Framework

- React (Vite)

---

## 🧭 Routing

- React Router
- Page-based navigation

---

## 📦 Structure

- components → reusable UI
- pages → main views
- services → API calls

---

## 🧠 State Management

- Local state (useState/useEffect)
- Potential future: Context API or Redux

---

## 🎯 UI Goals

- simple
- clean
- distraction-free

---

## 📱 Responsiveness

- mobile-first design
- flexible layouts

---

## ⚡ UX Considerations

- loading states
- error messages
- empty states
