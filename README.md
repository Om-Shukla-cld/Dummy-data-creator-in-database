# Dummy-data-creator-in-database
Generating random data in database backend just by clicking a button on frontend . using MongoDB , Mongoose , Express , EJS , Javascrpit


# Random Employee Data Generator

A full-stack web application that generates random employee data in the backend database by clicking a button on the frontend. This project demonstrates frontend–backend interaction using Express, EJS, MongoDB, and Mongoose.

---

## 🚀 Project Overview

The Random Employee Data Generator allows users to create multiple employee records in a MongoDB database with a single click. When the user clicks the **Generate Now** button on the frontend, the backend generates random employee data and stores it securely in the database using Mongoose models.

This project is ideal for understanding how frontend events trigger backend logic and database operations in a Node.js application.

---

## ✨ Features

- One-click random data generation
- Backend data creation using MongoDB
- Mongoose schema and model usage
- Express.js routing
- Server-side rendering with EJS
- Randomized employee details (name, salary, language, city, manager status)
- Responsive UI using Bootstrap
- Clean and modular project structure

---

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript
- Bootstrap
- EJS (Embedded JavaScript Templates)

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose (ODM)

---

## 📁 Project Structure

project/
│── models/
│ └── Employess.js
│── views/
│ └── index.ejs
│── main.js
│── package.json


---

## ⚙️ How the Application Works

1. The user opens the application in the browser.
2. Clicking the **Generate Now** button sends a request to the `/generate` route.
3. The backend generates random employee data.
4. Data is inserted into the MongoDB database using Mongoose.
5. Generated records are logged and stored successfully.

---

## 🧪 Random Data Fields

Each employee record includes:
- Name
- Salary
- Programming Language
- City
- Manager Status (true or false)

---

## 🔧 Installation & Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/random-employee-data-generator.git

**Step 2: Install Dependencies**
npm install

**Step 3: Start MongoDB**

Make sure MongoDB is running locally:

mongodb://localhost:27017/company

**Step 4: Run the Application**
node main.js

**Step 5: Open in Browser**
http://localhost:3000

**📌 Learning Outcomes**

Frontend to backend communication

Working with MongoDB and Mongoose schemas

Handling user-triggered backend operations

Generating random data programmatically

Using EJS for dynamic server-side rendering

Structuring a real-world Node.js project

**👤 Author**

Sanskar Gupta
