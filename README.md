# PyPassword-Manager 🔐

---

## Overview

A lightweight, interactive Python CLI tool designed to generate, store, and manage your account credentials directly from your terminal. 
It features a "typewriter" animation effect for a more immersive console experience.

---

## 🚀 C Features

- **Secure Generation:** Create random, high-entropy passwords using a mix of alphanumeric characters and special symbols.

- **CRUD Operations:** Create, Read, Update, and Delete account credentials easily.

- **Typewriter UI:** All output is rendered with a customizable "smooth flow" delay for a classic terminal aesthetic.

- **Error Handling:** Robust input validation to prevent crashes during menu navigation.

---

## 🛠️ How It Works

The application uses a nested dictionary structure to map account names to their respective usernames and passwords.

**Note**: In its current state, data is stored in memory. For long-term use, consider adding file I/O (like JSON or SQLite) to persist data after the script closes.

- Character Sets Used for Generation:

- Numbers: 12345678910

- Letters: Lowercase (a-z) and Uppercase (A-Z)

- Symbols: !@#$%^&*()-_+=[]\{}|;:',.<>/?~`

---

## 📦 Installation & Usage

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/terminal-password-manager.git
```
```bash
cd terminal-password-manager
```
### 2. Run the script: Ensure you have Python 3.x installed.
```bash
python main.py
```
### 3. Navigate the Menu: Simply enter the number corresponding to your desired action.

---

## 🖥️ Preview

| Option | Action             | Description                                           |
|--------|--------------------|-------------------------------------------------------|
| 1      | Store Password     | Save a new account, username, and password.           |
| 4      | Show Password      | Retrieve credentials for a specific account.          |
| 5      | Suggest Password   | Generate 3 random secure passwords.                   |
| 7      | Exit               | Safely close the application.                         |

---

## 🛡️ Security Disclaimer

This script is a demonstration tool. It stores passwords in plain text within the application's memory.
For production use, always use encryption libraries like cryptography to hash or encrypt sensitive data before storage.

---

## 📜 License

This project is licensed under the MIT License. See the  [**LICENSE**](/LICENSE) file for more details.
