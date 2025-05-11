# To-do-list-
Here's a sample GitHub `README.md` post for your **Simple Blog Website using Node.js, Express, and EJS**:

---

# 📝 Simple Blog Website

A basic blog website built with **Node.js**, **Express.js**, and **EJS templating engine**. Users can compose and view blog posts. This is a great beginner-friendly project to understand routing, templating, and handling POST requests in Express.

---

## 🔧 Technologies Used

* Node.js
* Express.js
* EJS
* Body-Parser
* HTML/CSS

---

## 🚀 Features

* Home page displays all blog posts.
* Users can compose and submit new posts.
* Static pages for "About" and "Contact".
* Posts stored in a temporary in-memory array (no database yet).

---

## 📸 Screenshots

> 
![Screenshot 2025-05-11 104928](https://github.com/user-attachments/assets/5995d0d0-f27f-435e-984a-e169aad57301)

---

## 📁 Folder Structure

```
project-folder/
│
├── views/
│   ├── home.ejs
│   ├── about.ejs
│   ├── contact.ejs
│   └── compose.ejs
│
├── public/
│   └── (static files like CSS/images)
│
├── app.js
├── package.json
└── README.md
```

---

## 🔄 How It Works

1. Visit `/` to see the homepage with existing posts.
2. Visit `/compose` to write a new post.
3. After submitting, you’ll be redirected back to the home page where your post appears.

---

## 📦 Installation

```bash
git clone https://github.com/your-username/simple-blog-nodejs.git
cd simple-blog-nodejs
npm install
node app.js
```

Open your browser and go to `http://localhost:3000`.
