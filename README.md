Connexta (REST API & Backend Architecture)
==========================================

> **🚧 Project Status: Backend Complete / Frontend Paused** The backend RESTful API (Node/Express/MongoDB) is fully implemented, featuring JWT authentication, complex database relationships, and secure data handling. The React frontend is currently paused and was primarily used as a client-side testing environment for API integration.

**Connexta** is a networking and outreach tracker designed to help professionals manage their connections, follow-ups, and next actions. This repository serves as a showcase for building a robust, secure, and scalable MERN stack backend.

* * * * *

⚙️ Core Backend Features
------------------------

-   **Secure User Authentication**: Full signup/login flow utilizing JWT (JSON Web Tokens) and bcrypt password hashing.

-   **Relational Database Design**: Complex Mongoose models linking Users to their specific Contacts and Interaction Timelines.

-   **Full CRUD API**: Endpoints to add, edit, delete, and categorize contacts and pipeline stages (Prospect → Reached Out → Scheduled, etc.).

-   **Filtering & Search Logic**: Backend controllers optimized to quickly query and return specific contacts by name, company, or pipeline stage.

🖥️ Client-Side Testing (React)
-------------------------------

*Note: The frontend is a paused work-in-progress used to validate API responses.*

-   React Router v6 for navigation.

-   React Hook Form for payload structuring.

-   Tailwind CSS for rapid prototyping.

* * * * *

🛠️ Tech Stack
--------------

**Backend**: Node.js, Express, MongoDB, Mongoose, JWT, bcrypt **Frontend**: React, React Router v6, React Hook Form, Tailwind CSS

**Dev Tools**: Nodemon, Postman, ESLint, Prettier

* * * * *

🚀 Getting Started
------------------

### Prerequisites

-   Node.js v18+

-   MongoDB (local or Atlas)

-   npm or yarn

### 1\. Backend Setup (Primary)

Navigate to the backend directory and install dependencies:

```
cd backend
npm install

```

Create a `.env` file based on `.env.example` and add your MongoDB URI and JWT secret. Start the development server:



```
npm run dev

```

### 2\. Frontend Setup (Optional/Testing)

Navigate to the frontend directory:



```
cd frontend
npm install
npm run dev
```
