# TrendHive – Product Listing

An e-commerce **product-listing** interface built with the MERN tech stack (MongoDB, Express, React, Node.js), featuring secure auth, admin controls, and smooth shopping flows.

---

## 🚀 Features

- **User Authentication**: Sign-up & sign-in with JWT‑based sessions.
- **Admin Dashboard**: Create, edit, delete products; manage listings.
- **Product Listings**:
  - Browse, filter, and search products.
  - View detailed product pages.
- **Shopping Cart & Checkout**:
  - Add/remove items, adjust quantities.
  - Checkout flow (mock or real payment integration).
- **Product Reviews**: Users can leave ratings and comments.
- **Responsive Design**: Mobile-first UI for all devices.

---

## 🛠️ Tech Stack

| Layer     | Technology              |
|-----------|--------------------------|
| Backend   | Node.js, Express.js      |
| Database  | MongoDB (Mongoose ODM)   |
| Frontend  | React, Redux / Context   |
| UI        | CSS / Bootstrap / Tailwind |
| Auth      | JWT, bcrypt             |
| Deployment| Heroku / Vercel / AWS   |

---

## 📁 Project Structure

/
├── backend/ # API and DB logic
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
├── frontend/ # React client
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── store/
│ └── public/
├── .gitignore
├── package.json
└── README.md

## 🔧 Setup & Run

1. Clone repo  
2. Install dependencies  
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

## App Running

Frontend runs on http://localhost:3000
Backend runs on http://localhost:9000
