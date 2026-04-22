# IntelliQuiz – Full Stack Quiz Web Application

A full-stack quiz web application built using Flask and MySQL, featuring secure user authentication, real-time quiz generation via API integration, and persistent performance tracking. Designed with production-ready practices including environment-based configuration and deployment on cloud platforms.

---

## 🔥 Features

* User signup, login, logout
* Secure password hashing using Werkzeug
* Dynamic quiz questions (Open Trivia API)
* Score calculation with result feedback
* Quiz history tracking for logged-in users
* Forgot password & delete account functionality
* Session management
* Responsive UI with Bootstrap

---

## 🚀 Key Highlights

- Implemented environment-based database configuration for both local and cloud deployments.
- Handled real-world deployment challenges including MySQL connectivity and service configuration.
- Designed modular Flask architecture with clear separation of routes, templates, and static assets.

---

## 🧠 Tech Stack

| Technology | Description                |
| ---------- | -------------------------- |
| Python     | Backend logic              |
| Flask      | Web framework              |
| MySQL      | Database (Railway + Local) |
| HTML / CSS | Frontend                   |
| Bootstrap  | Responsive UI              |
| JavaScript | Quiz logic & API calls     |
| Gunicorn   | Production WSGI server     |
| Railway    | Deployment platform        |

---

## 📁 Project Structure

```
quiz_flask_app/
│
├── app.py
├── requirements.txt
├── Procfile
├── .env.example
├── db/
│   └── schema.sql
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── app.js
│   └── favicon/
│       └── intelliquiz-favicon.svg
├── templates/
│   ├── welcome.html
│   ├── signup.html
│   ├── login.html
│   ├── index.html
│   ├── quiz.html
│   ├── result.html
│   ├── history.html
│   └── forgot-password.html
└── screenshots/
```
---


## 🖼️ Screenshots

🖼️ Screenshots

Homepage:  
![Homepage] (static/screenshots/homepage.png)

Login page:  
![Login] (static/screenshots/login.png)

Signup page:  
![Signup] (static/screenshots/signup.png)

Quiz page:  
![Quiz] (static/screenshots/quiz.png)

History page:  
![History] (static/screenshots/history.png)

Result page:  
![Result] (static/screenshots/result.png)
---

## 👤 Author

**Jatin Morwal**

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub — it really helps!
