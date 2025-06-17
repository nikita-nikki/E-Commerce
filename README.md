## 🛒 MERN E-Commerce Store

A full-stack e-commerce web application built with the MERN stack. This platform supports product listings, user authentication, cart management, order processing, and more—providing a modern and responsive shopping experience.

---

### 🚀 Features

- User authentication & authorization (JWT)
- Product browsing with search and filters
- Category-based product organization
- Shopping cart functionality
- Order placement & management
- Admin dashboard to manage products, users, and orders
- RESTful APIs with Express
- MongoDB as the primary database
- Responsive React frontend

---

### 🧑‍💻 Tech Stack

- **Frontend:** React, React Router, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT
- **State Management:** Context API / useReducer
- **Styling:** CSS (custom / frameworks)

---

### 📁 Folder Structure

```
MERN-E-Commerce-Store-main/
├── backend/        # Node.js + Express API
├── frontend/       # React client
├── .env            # Environment variables
├── example-env.env # Sample environment variables
├── package.json    # Root dependencies
```

---

### ⚙️ Environment Variables

Create a `.env` file in the root directory and populate it based on `example-env.env`. Example:

```bash
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

---

### 💡 Getting Started

#### 1. Clone the repository

```bash
git clone https://github.com/your-username/MERN-E-Commerce-Store.git
cd MERN-E-Commerce-Store
```

#### 2. Install dependencies

```bash
# Root-level dependencies
npm install

# Backend dependencies
cd backend
npm install

# Frontend dependencies
cd ../frontend
npm install
```

#### 3. Run the app

```bash
# In one terminal
cd backend
npm run dev

# In another terminal
cd frontend
npm start
```

---

###
