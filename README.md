# Password Strength Checker (GUI)

---

## 1. Project Title
**Password Strength Checker (GUI)** — A Python-based desktop application that analyzes the strength of user-entered passwords through a simple and intuitive graphical interface.

---

## 2. Project Description
This project is designed to help users understand how secure their passwords are by analyzing several key characteristics such as length, character variety, repeated characters, and more.  

It uses **Python’s Tkinter library** to create a clean graphical interface where users can input a password and receive instant feedback through color-coded message boxes (Green, Yellow, or Red).  

### What the application does:
- Evaluates passwords for strength using multiple security criteria  
- Prevents insecure inputs (spaces, short length, repeated characters, and common passwords)  
- Provides feedback via a user-friendly GUI  

### Why these technologies:
- **Python** for simplicity and readability  
- **Tkinter** (built-in GUI library) for creating a lightweight desktop interface without external dependencies  

### Challenges and future goals:
- Challenge: Handling multiple edge cases (like long repeated characters or space errors)  
- Future features:
  - A live progress bar for password strength
  - Password suggestions for improvement
  - Dark mode GUI
  - Integration with password databases to detect breached passwords  

---

## 3. Table of Contents
1. [Project Title](#1-project-title)  
2. [Project Description](#2-project-description)  
3. [Table of Contents](#3-table-of-contents)  
4. [How to Install and Run the Project](#4-how-to-install-and-run-the-project)  
5. [How to Use the Project](#5-how-to-use-the-project)  
6. [Credits](#6-credits)  
7. [Add a License](#7-add-a-license)  

---
## 4. How to Install and Run the Project

### Dependencies
- Python 3.x  
- Tkinter (comes pre-installed with Python)  
- Operating System: Works on **Windows, macOS, and Linux**

### Installation Steps
1. Clone this repository to your local machine:
   git clone https://github.com/SuperZhantor/password-strength-checker.git
2. Navigate into the project folder:
  cd password-strength-checker
3. Run the program:
  python password_checker.py

---

## 5. How to Use the Project

1. Open the program using the command above.
2. A GUI window will appear asking for your password.
3. Enter any password you want to test.
4. Click “Check Password” to analyze it.
5. Depending on the strength, you’ll receive one of the following pop-ups:
   - Strong Password — Excellent security
   - Medium Password — Needs improvement
   - Weak Password — Not secure


---

## 6. Credits

- Email: [Zhantore Shaikenov](mailto:zhantore321@gmail.com)
- GitHub: [Zhantore Shaikenov](https://github.com/SuperZhantor)


---

# 7. License
MIT License

Copyright (c) 2025 Zhantore Shaikenov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

