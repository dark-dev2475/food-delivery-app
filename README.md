# 🍽️ Zosh Food – MERN Stack Food Ordering App

A full-featured Food Ordering Web App built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It enables users to browse menus, add food items to cart, place orders, and allows admins to manage restaurants, categories, ingredients, and orders.

---

## 🚀 Features

### 👥 User Side
- User registration and login (JWT based)
- Browse restaurants and menu items
- Filter by category and ingredients
- Add to cart and place orders
- View order history
- **Secure online payments using Stripe**

### 🛠️ Admin Panel
- Manage restaurants, food categories, and ingredients
- Add/edit/delete food items
- View and update order status

---

## 💳 Stripe Payment Integration

Users can seamlessly pay online for their food orders using **Stripe Checkout**. Payments are securely handled on the backend and integrated with order flow.

- Tested with Stripe test mode
- Token-based secure payment flow
- Payment confirmation reflected in order status

## 🧑‍💻 Tech Stack

- **Frontend:** React.js, React Router, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **API Testing:** Postman 

---

## 📂 Folder Structure

food-ordering-mern/
├── frontend/ # React frontend
├── backend/ # Node.js & Express backend
├── project setup steps.txt






---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/food-ordering-mern.git
cd food-ordering-mern

cd backend
npm install
# Add .env file with required variables (Mongo URI, JWT_SECRET, etc.)
npm start


cd ../frontend
npm install
npm start
