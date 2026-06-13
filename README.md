# 🔐 Secure Login System (Flask Web App)

A secure authentication system built using Flask that allows users to register, login, and logout with proper password hashing using bcrypt. It uses session management to maintain user login state and ensures basic security practices like input validation.

## 🚀 Features
User registration and login system, password hashing using bcrypt for security, session management with login/logout functionality, input validation, and SQLite database integration for storing user credentials securely.

## 🛠️ Tech Stack
Python, Flask, Flask-Bcrypt, SQLite, HTML, CSS

## 📁 Project Structure
secure-login-system/  
│── app.py  
│── database.db  
│── requirements.txt  
│── templates/ (login.html, register.html, dashboard.html)  
│── static/ (style.css)  

## ⚙️ How to Run
Clone the repository using git clone https://github.com/your-username/secure-login-system.git, then install dependencies using pip install -r requirements.txt, and finally run the app using python app.py. Open http://127.0.0.1:5000 in your browser.

## 🔐 Security Features
Passwords are stored using bcrypt hashing instead of plain text, sessions are used for authentication, input validation prevents invalid data, and database queries are structured to avoid common security risks.

## 📸 Output Flow
User registers → Login → Dashboard access → Logout securely

## 👨‍💻 Author
GUNDALA VARSHA

## ⭐ Future Improvements
Add Two-Factor Authentication (2FA), password reset system, email verification, JWT authentication, admin dashboard, and deploy on cloud platforms like Render or AWS.

## 🏆 Conclusion
This project demonstrates a secure login system built using Flask with proper authentication, password hashing, and session management suitable for real-world web applications.
