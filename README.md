<div align="center">

# 🔐 Password Strength Checker

### A responsive frontend web application that analyzes password security in real-time using entropy calculations, character type detection, and pattern recognition.

<p>
  <a href="https://your-live-demo-link.com">
    <img src="https://img.shields.io/badge/🌐-Live_Demo-success?style=for-the-badge" alt="Live Demo">
  </a>
</p>

</div>

---

## 📋 Table of Contents

- 📖 About The Project
- ✨ Features
- 🛠️ Tech Stack
- 🚀 Usage
- 📁 Project Structure
- 🧠 Key Algorithms
- 🔄 From C++ DSA Project to Web Application
- 📊 Password Scoring Breakdown
- 👩‍💻 Author
- 📄 License
- ⭐ Show Your Support

---

# 📖 About The Project

This project is a **Password Strength Checker** that provides instant security analysis as you type. Originally developed as a C++ console application for a Data Structures and Algorithms (DSA) project, it has been converted into a fully responsive single-page web application.

The tool evaluates password strength using:

- **Entropy calculation** – Measures randomness based on character set size and password length
- **Character type detection** – Identifies uppercase, lowercase, digits, and symbols
- **Pattern recognition** – Detects sequential numbers, repeated characters, and keyboard patterns
- **Common password check** – Compares against a list of commonly used passwords

The application provides actionable feedback to help users create stronger, more secure passwords.

---

# ✨ Features

<table>
<tr>
<td>✅ <b>Real-time Analysis</b></td>
<td>Instant feedback as you type</td>
</tr>

<tr>
<td>📊 <b>Dynamic Scoring</b></td>
<td>0-10 score with visual indicators</td>
</tr>

<tr>
<td>📈 <b>Strength Bar</b></td>
<td>Visual representation of password strength</td>
</tr>

<tr>
<td>👁️ <b>Password Visibility Toggle</b></td>
<td>Show/hide password option</td>
</tr>

<tr>
<td>✔️ <b>Requirements Checklist</b></td>
<td>Live validation of security criteria</td>
</tr>

<tr>
<td>🧮 <b>Entropy Measurement</b></td>
<td>Shows password randomness in bits</td>
</tr>

<tr>
<td>⏳ <b>Time to Crack</b></td>
<td>Estimated time to brute-force the password</td>
</tr>

<tr>
<td>🏷️ <b>Character Type Badges</b></td>
<td>Shows which character types are used</td>
</tr>

<tr>
<td>💡 <b>Strengths & Issues</b></td>
<td>Actionable feedback with recommendations</td>
</tr>

<tr>
<td>📱 <b>Responsive Design</b></td>
<td>Works on all devices (mobile, tablet, desktop)</td>
</tr>

<tr>
<td>🚫 <b>No External Dependencies</b></td>
<td>Pure HTML5, CSS3, and Vanilla JavaScript</td>
</tr>
</table>

---

# 🛠️ Tech Stack

<div align="center">

| Technology | Purpose |
|:----------:|:--------|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Styling, animations, responsive design |
| **JavaScript (Vanilla)** | All logic, DOM manipulation, event handling |
| **Internal CSS & JS** | Single-file implementation (no external dependencies) |

</div>

---

# 🚀 Usage

```text
1. Open the index.html file in any modern web browser

2. Type your password in the input field

3. View instant analysis including:

   • Score (0-10)
   • Rating (Very Weak → Strong)
   • Entropy (in bits)
   • Estimated time to crack
   • Requirements checklist
   • Strengths and recommendations
   • Character types used
```

> **No installation, setup, or server required. Everything runs in the browser.**

---

# 📁 Project Structure

```text
password-strength-checker/
│
├── index.html          # Complete application (HTML + CSS + JS)
├── README.md           # Project documentation
└── LICENSE             # MIT License
```

> The entire application is contained in a single HTML file with internal CSS and JavaScript.

---

# 🧠 Key Algorithms

<div align="center">

| Algorithm | Description |
|-----------|-------------|
| **Entropy Calculation** | `Entropy = Length × log2(Charset)` |
| **Score Calculation** | Based on length, character variety, and entropy |
| **Pattern Detection** | Sequential numbers, repeated chars, keyboard patterns |
| **Common Password Check** | Hash set lookup against common passwords list |

</div>

---

# 🔄 From C++ DSA Project to Web Application

This project began as a C++ console application that demonstrated:

- **Data Structures** – Linked List for common passwords, Queue for sequential pattern detection
- **Algorithms** – Password analysis, entropy calculation, pattern matching

### Conversion Process

- ✅ Retained all core analysis logic
- ✅ Transformed console output to responsive web UI
- ✅ Added real-time interactivity
- ✅ Implemented visual feedback system
- ✅ Enhanced user experience with modern design

---

# 📊 Password Scoring Breakdown

<div align="center">

| Criteria | Points |
|----------|--------|
| **Length 15+** | +4 |
| **Length 12-14** | +3 |
| **Length 8-11** | +2 |
| **4 Character Types** | +3 |
| **3 Character Types** | +2 |
| **2 Character Types** | +1 |
| **Entropy 70+** | +3 |
| **Entropy 50-69** | +2 |
| **Entropy 30-49** | +1 |

</div>

> **Final Score:** Minimum of 10 points

---

<div align="center">

# 👩‍💻 Author

## **Marjan Yousafzai**

**Frontend Developer | Security Enthusiast**

<br>

<a href="https://github.com/yousafzai05/yousafzai05">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
</a>

<a href="https://www.linkedin.com/in/marjan-yousafzai/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<a href="mailto:yousafzaimarjan05@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>

</div>

---

# 📄 License

This project is licensed under the MIT License - see the **LICENSE** file for details.

```text
MIT License
Copyright (c) 2024 Marjan Yousafzai
```

---

<div align="center">

# ⭐ Show Your Support

If you found this project useful, please consider giving it a ⭐ on GitHub!

</div>
