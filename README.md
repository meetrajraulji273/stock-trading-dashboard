# Stock Trading Dashboard

A web application built using the MERN stack (MongoDB, Express, React, Node.js) that allows users to buy and sell stocks, view analytics, and manage their portfolio. It includes a landing page, a user dashboard, and other related features.

---

## Features

- ✅ User authentication and authorization
- 📊 View stock analytics (charts, historical data, etc.)
- 💸 Buy and sell stocks
- 📁 Manage stock portfolio
- 🏠 Landing page with project overview
- 📂 Dashboard to access trading and analytics features

---

## Tech Stack

- **Frontend:** React, Tailwind CSS / CSS Modules (if used)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Others:** JWT for auth, Charting library for analytics (e.g., Chart.js, Recharts)

---

## Installation

### Prerequisites

- Node.js and npm
- MongoDB (local or Atlas)

### Clone the repository

```bash
git clone https://github.com/your-username/stock-trading-dashboard.git
cd stock-trading-dashboard

Setup Backend
bash
Copy
Edit
cd backend
npm install
npm run dev

Make sure to set up your .env file with:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret

Setup Frontend
bash
Copy
Edit
cd frontend
npm install
npm start