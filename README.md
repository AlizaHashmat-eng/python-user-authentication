# Python User Authentication System

![Flask](https://img.shields.io/badge/Flask-v2.0.1-blue.svg) 
![License](https://img.shields.io/badge/license-MIT-green.svg) 
![Status](https://img.shields.io/badge/status-Active-brightgreen.svg) 
![Contributions](https://img.shields.io/badge/contributions-welcome-orange.svg)

Welcome to the **Python User Authentication System** created by **Aliza Hashmat**. This project is designed to handle user registration, login, logout, and session management using **Flask**, with secure password hashing and session handling.

---

## 🛠️ Features

- **User Registration**: Sign up users with secure password hashing.
- **User Login**: User authentication and session management.
- **Password Hashing**: Secure password storage using **Flask-Bcrypt**.
- **Session Management**: User sessions using **Flask-Login**.
- **Logout Functionality**: Secure user logout.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AlizaHashmat-eng/python-user-authentication.git
cd python-user-authentication
```

### 2. Set Up the Virtual Environment

Create and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate
```

### 3. Install Dependencies

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### 4. Configure the Application

Update `config.py` with your secret key and database URI:

```python
SECRET_KEY = 'your-secret-key'
SQLALCHEMY_DATABASE_URI = 'sqlite:///site.db'  # or your preferred database
```

### 5. Run the Application

Start the Flask app:

```bash
python run.py
```

Visit `http://127.0.0.1:5000` in your browser to view the application.

---

## 📦 Project Structure

```plaintext
python-user-authentication/
├── app/
│   ├── __init__.py           # Flask app initialization
│   ├── routes.py             # Routes for login, signup, etc.
│   ├── models.py             # Database models
│   ├── templates/            # HTML templates
│   ├── static/               # CSS, JS files
│   └── forms.py              # Form handling with WTForms
├── config.py                 # Configuration file
├── requirements.txt          # Dependencies
├── run.py                    # Application entry point
├── README.md                 # Project documentation
└── venv/                     # Virtual environment (optional)
```

---

## 📋 Dependencies

- **Flask**: Web framework for Python
- **Flask-SQLAlchemy**: ORM for database interactions
- **Flask-WTF**: Form handling and validation
- **Flask-Login**: User session management
- **Flask-Bcrypt**: Password hashing for security

Install dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🛠️ User Authentication Workflow

- **Registration**: Users can register with email and password. Passwords are hashed before being stored in the database.
- **Login**: Registered users can log in. Sessions are handled using **Flask-Login**.
- **Logout**: Users can log out securely.

---

## 📈 Badges & Project Info

![GitHub stars](https://img.shields.io/github/stars/AlizaHashmat-eng/python-user-authentication.svg) ![GitHub forks](https://img.shields.io/github/forks/AlizaHashmat-eng/python-user-authentication.svg) ![GitHub issues](https://img.shields.io/github/issues/AlizaHashmat-eng/python-user-authentication.svg)

---

## 👨‍💻 Contributing

If you want to contribute, feel free to fork the project and submit a pull request. Contributions are always welcome!

---

## 📧 Contact

This project is developed and maintained by **Aliza Hashmat**.  
Feel free to reach out via email: [aliza.1801014@gmail.com](mailto:aliza.1801014@gmail.com).

---

## ⚖️ License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

### ⭐ If you found this project useful, consider giving it a star on GitHub! ⭐

[![GitHub Follow](https://img.shields.io/github/followers/AlizaHashmat-eng?label=Follow&style=social)](https://github.com/AlizaHashmat-eng) [![GitHub Star](https://img.shields.io/github/stars/AlizaHashmat-eng/python-user-authentication?style=social)](https://github.com/AlizaHashmat-eng/python-user-authentication/stargazers) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Aliza%20Hashmat-blue)](https://www.linkedin.com/in/aliza-hashmat)
```
