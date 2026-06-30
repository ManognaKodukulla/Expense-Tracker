# Expense Management System

A full-stack Expense Management System built using the MERN stack that enables users to securely manage their income and expenses, monitor spending patterns, and visualize financial data through an interactive dashboard.

---


##  Features

-  JWT-based user authentication and authorization
-  Add, edit, and delete income & expense transactions
-  Categorize transactions for better financial management
-  Interactive dashboard with spending summaries and charts
-  Track transactions by date and category
-  Responsive user interface for desktop and mobile devices

---

##  Tech Stack

### Frontend
- React.js
- JavaScript
- CSS
- Bootstrap
- Material Icons

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JSON Web Token (JWT)

---

##  Installation

Clone the repository

```bash
git clone https://github.com/ManognaKodukulla/Expense-Tracker.git
```

Go to the project directory

```bash
cd Expense-Tracker
```

Install frontend dependencies

```bash
cd frontend
npm install
```

Install backend dependencies

```bash
cd ../backend
npm install
```

Create a configuration file

```
backend/config/config.env
```

Add the following environment variables

```env
PORT=5000
MONGO_URL=mongodb+srv://manogna_db_user:QManny_17@cluster0.s7d2nwq.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET=QManny_17
```

Run the frontend

```bash
cd frontend
npm start
```

Run the backend

```bash
cd backend
npm run dev
```

---

## Project Structure

```
Expense-Tracker
│
├── frontend
├── backend
├── README.md
```

---


## 👩‍💻 Author

**Manogna Kodukulla**

GitHub:
https://github.com/ManognaKodukulla

---

## 📄 License

This project is licensed under the MIT License.

