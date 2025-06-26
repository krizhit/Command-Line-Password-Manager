# 🔐 Command-Line Password Manager

## 🧾 Description

A secure Python CLI application that stores and retrieves encrypted passwords using a master key. Built with AES encryption and `getpass`, it keeps your credentials safe and local.

---

## ✨ Features

- Master password authentication  
- Remember multiple site credentials securely  
- AES encryption using Fernet (`cryptography`)  
- Stores data in a local JSON vault file  
- View saved passwords only after successful login  
- Easy to use, secure, and portable  

---

## 💻 Technologies Used

- Python 3.x  
- `cryptography` (for AES encryption)  
- `getpass` (for secure password entry)  
- `json` (for local data storage)  

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/krizhit/Command-Line-Password-Manager.git
   cd cli-password-manager
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   ```

   **For Windows:**
   ```bash
   .venv\Scripts\activate
   ```

   **For macOS/Linux:**
   ```bash
   source .venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install cryptography
   ```

4. Run the application:
   ```bash
   python Command-Line Password Manager.py
   ```
