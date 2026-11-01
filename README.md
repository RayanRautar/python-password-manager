# Python Password Manager 🔐

A secure and simple command-line password manager built in Python. This project allows users to securely store, encrypt, and view credentials locally using symmetric encryption.

## Features
- **Secure Encryption:** Uses the `cryptography` library (Fernet symmetric encryption) to ensure sensitive passwords are never stored in plain text.
- **Local File Management:** Safely reads and writes credentials using local text files (`passwords.txt` and `key.key`).
- **Interactive Command-Line Interface:** Easy-to-use menu allowing users to add new accounts, view decrypted credentials, or quit.

## Tech Stack
- **Language:** Python 3
- **Library:** `cryptography`

## How to Run
1. Make sure you have Python installed along with the cryptography library:
   ```bash
   pip install cryptography
