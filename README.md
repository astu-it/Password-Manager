
# 🔐 Password Manager

A simple command-line password manager built with Python. It securely stores and retrieves passwords using encryption.

## Features

- Encrypts passwords using Fernet encryption
- Stores usernames and passwords securely
- Add new credentials
- View saved credentials
- Simple command-line interface

## Technologies Used

- Python 3
- cryptography (Fernet)

## Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Password-Manager.git
```

2. Move into the project folder

```bash
cd Password-Manager
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the program

```bash
python main.py
```

## Project Structure

```
Password-Manager/
│── main.py
│── key.key
│── passwords.txt
│── requirements.txt
│── README.md
```

## What I Learned

- File handling in Python
- Encryption using Fernet
- Managing sensitive data securely
- Writing reusable functions
- Building a real-world Python project

## Future Improvements

- Master password authentication
- Password generator
- Search functionality
- GUI version
- Database storage instead of text files

## Disclaimer

This project was created for learning purposes and should not be used to store sensitive passwords without additional security improvements.
