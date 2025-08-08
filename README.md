# 🌍 Capital City Quiz App

An interactive quiz game where you guess the capital city of a given country. Built with **Express.js**, **EJS**, **PostgreSQL**, and **vanilla JavaScript**, this project tests your geography knowledge and keeps score — but one wrong answer ends the game!

---

## 🎮 How It Works

- The app pulls all world capitals from a PostgreSQL database.
- You're shown a random country and asked to enter its capital.
- If you're right, you move on and your score increases.
- If you're wrong — game over. Restart to try again!

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS, HTML5, CSS3, JavaScript
- **Database**: PostgreSQL
- **Other**: Body-parser, PG (node-postgres)

---

## 📁 Project Structure

World_Capitals/
├── public/
│ ├── styles/
│ │ └── main.css
│ └── images/ # Backgrounds, etc.
├── views/
│ └── index.ejs # Main quiz view
├── capitals.csv # Source data for DB (optional)
├── index.js # Express app logic
├── package.json
└── README.md

## Installation
npm install express body-parser pg

## Run your app
node index.js
Then go to http://localhost:3000 in your browser.
