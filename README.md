# **TechBlog**

*A clean and modern technical blogging platform built with Django.*

<div align="center">

![TechBlog Banner](./banner.png)

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.x-green.svg)](https://www.djangoproject.com/)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

</div>

---

## 🚀 **Overview**

**TechBlog** is a lightweight yet powerful blogging platform built with **Django**.
It is designed for developers and tech writers who want:

* A clean, distraction-free writing experience
* A fast and extensible backend
* Simple deployment and easy customization

Whether you're sharing tutorials, documenting your learning, or building a personal dev blog, **TechBlog** is a solid foundation.

---

## ✨ **Features**

* 📝 Create, edit & delete blog posts via Django Admin
* 📄 Clean, responsive frontend layout
* 🗂️ Post detail & listing pages
* 🧩 Modular structure for easy feature expansion
* 🛡️ Secure & production-ready Django architecture
* ⚡ Fast development with built-in Django tools

---

## 🧰 **Tech Stack**

| Layer           | Technology       |
| --------------- | ---------------- |
| **Backend**     | Django (Python)  |
| **Frontend**    | HTML, CSS        |
| **Database**    | SQLite (default) |
| **Deployment**  | WSGI compatible  |
| **Environment** | Python venv      |

---

## 📸 **Screenshots**

> Replace the images below with actual screenshots from your project (`/assets` folder recommended).

### 🏠 Home Page

![Home Page](./assets/home.png)

### 📝 Blog Details

![Blog Details](./assets/details.png)

---

## 📦 **Installation & Setup**

Follow the steps below to run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ak-127/techblog.git
cd techblog
```

### 2️⃣ Create a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate   # macOS/Linux

venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Migrations

```bash
python manage.py migrate
```

### 5️⃣ Start the Development Server

```bash
python manage.py runserver
```

📍 App available at: **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**
📍 Admin panel at: **[http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)**

---

## 🗂️ **Project Structure**

```
techblog/
│
├── blog/                # Core blog app
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── techblog/            # Main project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py
└── requirements.txt
```

---

## 🔮 **Planned Enhancements**

Here are improvements that could elevate the platform:

* 🎨 Theming support (Dark/Light mode)
* 🏷️ Categories & Tags
* 💬 Comment system
* 🧵 Markdown or WYSIWYG editor
* 🔍 Search functionality
* 📊 Analytics dashboard
* 🧪 Unit tests & CI/CD integration
* ☁️ Deployment templates (Docker, Heroku, Render, etc.)

---

## 🤝 **Contributing**

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

   ```bash
   git checkout -b feature/my-feature
   ```
3. Commit changes
4. Open a Pull Request

Please follow existing coding style & include useful commit messages.


---

## 📬 **Contact**

**Author:** ak-127
🔗 GitHub: [https://github.com/ak-127](https://github.com/ak-127)
💬 Issues & PRs welcome!

---
