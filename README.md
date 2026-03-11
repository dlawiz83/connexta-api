# Connexta — Backend Learning Project

A MERN stack backend for a professional networking/CRM platform. 
Built to demonstrate REST API design, authentication, and database architecture patterns.

## 🎯 What This Showcases

**Core Backend Skills:**
- Secure JWT + bcrypt authentication
- Relational database design with MongoDB/Mongoose
- RESTful API patterns (CRUD operations)
- Backend filtering, search, and query optimization
- Error handling and validation

**Technical Implementation:**
- User authentication with JWT tokens
- Complex data relationships (Users → Contacts → Interaction Timeline)
- Pipeline stage management (Prospect → Reached Out → Scheduled)
- Search/filter by name, company, pipeline stage

## 🛠️ Tech Stack

**Backend:** Node.js | Express | MongoDB | Mongoose | JWT | bcrypt  
**Frontend:** React | React Router v6 | React Hook Form | Tailwind CSS  
**Dev Tools:** Nodemon, Postman, ESLint, Prettier

## 🚀 Quick Start

### Backend Setup
```bash
cd backend
npm install
```

Create a `.env` file with your MongoDB URI and JWT secret:
```
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```

Start the server:
```bash
npm run dev
```

### Frontend (Optional Testing Client)
```bash
cd frontend
npm install
npm run dev
```

## 📚 Learning Outcomes

This project demonstrates:
- How to structure a scalable Node/Express backend
- Secure authentication patterns
- Database relationship modeling
- API endpoint organization
- CRUD operation best practices

---

**Built as a learning project to understand MERN stack fundamentals.**
