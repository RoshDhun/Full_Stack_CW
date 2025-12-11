# Full Stack Development Coursework – SkillSphere

**Student Name:** ROSHNI DEVI DHUNPUTH  
**Student ID:** M00983700  
**Module:** CST3144 – Full Stack Development  
**Academic Year:** 2025/26

---

## 1. Vue.js App (Front-End)

- **GitHub Repository:**  
https://github.com/RoshDhun/Full_Stack_CW


This is the Vue.js single–page application (`page.html`) that implements:
- Lesson browsing with search, sort and filters  
- Shopping cart & checkout  
- Login / Sign up for parents  
- Connection to the Express.js REST API via `fetch()`.

---

## 2. Express.js App (Back-End)

- **GitHub Repository:**  
https://github.com/RoshDhun/Full_Stack_CW_backend

- **Hosted API (Render / AWS):**  
https://full-stack-cw-backend-p2lu.onrender.com

The Express.js app exposes a REST API using the native MongoDB Node.js driver:
- `GET /lessons` – returns all lessons from MongoDB Atlas  
- `GET /search?q=term` – server-side search on lessons  
- `POST /orders` – saves an order to the `order` collection  
- `PUT /lessons/:id` – updates the `spaces` field for a lesson  
- `POST /users/signup` and `POST /users/login` – basic email/password auth.

---



### Front-End

1. Open `Frontend` folder.  
2. Open `page.html` in a browser (or use VS Code Live Server).  

The app expects the back-end to be reachable at:

```text
https://full-stack-cw-backend-p2lu.onrender.com
