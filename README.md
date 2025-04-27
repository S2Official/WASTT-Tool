
# 🌐 WASTT — Web Application Security Testing Tool

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

---

**WASTT (Web Application Security Testing Tool)** is an intuitive, modular tool crafted for security professionals, penetration testers, and developers to assess and enhance the security of web applications.  
With a range of powerful testing modules, WASTT helps identify vulnerabilities like **SQL Injection**, **XSS**, **Directory Traversal**, and much more — all from a simple, user-friendly interface.

---

## 🚀 Features

- 🔎 **SQL Injection Testing (GET & POST)**  
  • Scans for potential SQL Injection vulnerabilities in both GET and POST request methods.

- ⚡ **Cross-Site Scripting (XSS) Detection**  
  • Identifies potential XSS vulnerabilities, allowing attackers to inject malicious scripts.

- 🗂️ **Directory Brute Force**  
  • Brute-forces common directories and file paths to uncover hidden endpoints or sensitive resources.

- 🛡️ **Web Application Firewall (WAF) Detection**  
  • Attempts to detect the presence of a WAF protecting the application.

---

## 📥 Installation

**Requirements**  
- Python 3.12 or higher
- `requests` and `termcolor` libraries

**Quick Setup**

```bash
# Clone the repository
git clone https://github.com/yourusername/wastt.git
cd wastt

# Install required dependencies
pip install -r requirements.txt

# Run the tool
python wastt.py
```

---

## 🛠️ Usage

After launching the tool, you'll be greeted with an interactive menu:

```plaintext
Welcome to WASTT - Web Application Security Testing Tool!

Choose an option:
[1] Test SQL Injection (GET)
[2] Test SQL Injection (POST)
[3] Test XSS
[4] Directory Bruteforce
[5] Detect WAF
[0] Exit
```

Simply select the desired test and input the target URL or IP address when prompted.

---

## ✨ Roadmap

- ✅ Improve XSS scanning capabilities with deeper payload analysis.
- 🔜 Enhance Server IP Vulnerability Scanning with CVE databases.
- 🔒 Implement automatic SQL Injection mitigation (input sanitization, prepared statements).
- 📚 Expand the module base for future vulnerabilities (e.g., CSRF, IDOR).

---

## 🤝 Contributing

Contributions are highly welcome! 🚀  
If you'd like to propose improvements, report bugs, or add new features:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

Let's make WASTT better together!

---

## ⚠️ Legal Disclaimer

> WASTT is provided for **educational and authorized security testing** only.
> - Use only on systems you own **or** have **explicit written permission** to test.
> - Unauthorized use of this tool against systems without consent is **illegal** and **unethical**.
> - The developers take **no responsibility** for misuse, damages, or legal consequences.

Use responsibly. Stay ethical. 🛡️

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

# ✨ Happy Hacking!
