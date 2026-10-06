# movie_app

A full-stack web application built with **Express.js**, **Tailwind CSS**, and **MongoDB**.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node.js](https://img.shields.io/badge/Node.js-v18%2B-green)
![Express](https://img.shields.io/badge/Express.js-4.x-lightgrey)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.x-38B2AC)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248)

---

## 🚀 Features

* **Responsive UI:** Built with Tailwind CSS for seamless viewing on desktop, tablet, and mobile.
* **RESTful API:** Express.js routing for handling HTTP requests and backend logic.
* **Database Integration:** MongoDB for efficient data storage, querying, and schema management.
* **Fast Performance:** Minimal dependencies and optimised static asset serving.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+)
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (via Mongoose / Native Driver)

---

## 📁 Project Structure

```text
├── public/              # Static files (CSS, images, JS)
├── views/               # HTML/Template files
├── config               # Database connection setup
├── .env.example         # Environment variables template
├── index.js            # Express app entry point
└── package.json         # Project metadata and dependencies
⚙️ Prerequisites
Ensure you have the following installed locally:

Node.js (v18 or higher)

npm or yarn

MongoDB running locally or a MongoDB Atlas connection string

📦 Installation & Setup
Clone the repository:

Bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
Install dependencies:

Bash
npm install
Configure Environment Variables:
Create a .env file in the root directory and add your configurations:

Code snippet
PORT=5000
MONGODB_URI=mongodb://localhost:27017/your_database_name
Build CSS (if using Tailwind CLI):

Bash
npm run build:css
Start the server:

Bash
# Development mode (with nodemon)
npm run dev

# Production mode
npm start
View in browser:
Open http://localhost:5000 to access the application.

