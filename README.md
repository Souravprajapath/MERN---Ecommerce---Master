#Ecommerce Web Application

A full-featured ecommerce application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This project includes essential features like user authentication, product management, cart functionality, order processing, and admin controls.

## 🚀 Features

- **User Authentication & Authorization** (JWT)
- **Admin Dashboard** for managing products, categories, and users
- **Product Listing & Filtering**
- **Shopping Cart & Checkout**
- **Order Placement & Order History**
- **Secure API** using Express and JWT
- **Responsive Design** with modern UI using React and Bootstrap

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Axios
- React Router
- Bootstrap

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Multer for image uploads

## 📁 Project Structure

```

mern-ecommerce-master/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── config/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
├── .env
├── package.json

````

## ⚙️ Setup Instructions

### Prerequisites
- Node.js and npm
- MongoDB installed locally or MongoDB Atlas

### 1. Clone the repository
```bash
git clone https://github.com/Souravprajapath/MERN---Ecommerce---Master.git
cd MERN---Ecommerce---Master
````

### 2. Set up environment variables

Create a `.env` file in the `backend/` directory and add:

```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

### 3. Install dependencies

```bash
# For backend
cd backend
npm install

# For frontend
cd ../frontend
npm install
```

### 4. Run the development servers

```bash
# Start backend
cd backend
npm run dev

# Start frontend
cd ../frontend
npm start
```

The app will run on:

* Frontend: `http://localhost:3000`
* Backend API: `http://localhost:5000`


---
