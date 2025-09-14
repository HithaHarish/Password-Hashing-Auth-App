# Password Hashing Authentication App

A simple Flask application demonstrating password hashing and authentication.

## Features
- User registration with hashed passwords
- User login with hashed password verification
- Simple session management
- SQLite database for user storage

## Setup Instructions
1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Run the app:
    ```bash
    python app.py
    ```

3. Open your browser at `http://127.0.0.1:5000`

## Note
Passwords are never stored in plain text. We use Werkzeug for secure password hashing.
