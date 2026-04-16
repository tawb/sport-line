# 🏬 Sport Line Store

### A Full-Stack E-Commerce Web Application

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.x-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**An end-to-end e-commerce platform for browsing and purchasing sporting goods — built with Flask, MySQL, and vanilla JavaScript.**

[Features](#-features) · [Tech Stack](#-tech-stack) · [Database Schema](#-database-schema) · [Installation](#-installation) · [Usage](#-usage) · [Project Structure](#-project-structure)

</div>

---

## 📌 About

**Sport Line Store** is a full-stack web application that simulates a real-world online store for sports products. Users can browse a product catalog, register/log in securely, manage a shopping cart, and place orders — all through a responsive, user-friendly interface.

This project was developed following the **full software development lifecycle**: requirements analysis, system design, implementation, and testing.

---

## ✨ Features

| Area | Details |
|---|---|
| **Product Catalog** | Browse sports products with images, descriptions, and pricing |
| **User Authentication** | Secure registration and login system with session management |
| **Shopping Cart** | Add, update quantity, and remove items in a persistent cart |
| **Order Processing** | Complete checkout flow from cart to confirmed order |
| **Responsive Design** | Mobile-friendly layout that adapts to all screen sizes |
| **Database-Driven** | All data (users, products, orders) stored and managed via MySQL |

---

## 🛠 Tech Stack

### Back-End
- **Python 3** — core server-side language
- **Flask** — lightweight web framework handling routing, sessions, and templating
- **MySQL** — relational database for persistent data storage

### Front-End
- **HTML5** — semantic page structure
- **CSS3** — styling and responsive layouts
- **JavaScript (ES6)** — client-side interactivity and dynamic UI updates

---


---

## ⚙ Installation

### Prerequisites

- Python 3.8+
- MySQL Server 8.0+
- pip (Python package manager)

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/<your-username>/sport-line-store.git
cd sport-line-store
```

**2. Create and activate a virtual environment**
```bash
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Set up the database**
```bash
mysql -u root -p < "projectt (2).sql"
```

**5. Configure environment variables**

Create a `.env` file in the project root:
```env
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your_secret_key_here
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_mysql_password
DB_NAME=sport_line_store
```

**6. Run the application**
```bash
flask run
```

The app will be available at `http://127.0.0.1:5000`.

---

## 🚀 Usage

| Action | How |
|---|---|
| **Browse Products** | Visit the homepage to explore the full product catalog |
| **Create an Account** | Click **Register** and fill in your details |
| **Log In** | Use your credentials to access your account |
| **Add to Cart** | Click the cart button on any product to add it |
| **Checkout** | Review your cart and confirm your order |

---

## 📁 Project Structure

```
sport-line-store/
│
├── app.py                  # Flask application entry point
├── requirements.txt        # Python dependencies
├── projectt (2).sql        # MySQL database schema
├── DataBase.bin            # Binary database export
│
├── templates/              # Jinja2 HTML templates
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── cart.html
│   └── ...
│
├── static/                 # Front-end assets
│   ├── css/
│   ├── js/
│   └── images/
│
└── README.md
```

---

## 📝 License

This project was developed for educational purposes.

---

<div align="center">

**Built with ❤️ using Flask & MySQL**

</div>
