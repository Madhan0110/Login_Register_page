# User Registration and Login System

This project is a simple web application built using Streamlit, Python, and SQLite that allows users to register and login

# FEATURES

- User registration with username and password
- Passwords are hashed using SHA-256 for security
- User login verification
- Stores user data securely in an SQLite database

# How to run

1. Install dependencies:

# pip install streamlit

2. Run the app:

# streamlit run app.py

# Code structure

- `app.py`: Main Streamlit application with registration and login
- `users.db`: SQLite database file for storing user credentials

# Security considerations

- Passwords are hashed using SHA-256 before storing
- SQLite is used for simplicity — for production, consider more robust DBMS and encryption

 
