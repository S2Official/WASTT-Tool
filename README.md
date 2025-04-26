# 🌐 WASTT — Web Application Security Testing Tool

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

---

**WASTT (Web Application Security Testing Tool)** is an intuitive, modular tool crafted for security professionals, penetration testers, and developers to assess and enhance the security of web applications.  
With a range of powerful testing modules, WASTT helps identify vulnerabilities like **SQL Injection**, **XSS**, **Directory Traversal**, and much more — all from a simple, user-friendly interface.

---

## 🚀 Features

- 🔎 **SQL Injection Testing**  
  • Scans for potential SQL Injection vulnerabilities where malicious queries could compromise your web app's backend.

- ⚡ **Cross-Site Scripting (XSS) Detection** *(In Progress)*  
  • Upcoming feature to identify XSS vulnerabilities that allow attackers to inject malicious scripts.

- 🗂️ **Directory Brute Force**  
  • Brute-forces common directories and file paths to uncover hidden endpoints or sensitive resources.

- 🛠️ **CMS Detection**  
  • Identifies if the target uses popular CMS platforms (WordPress, Joomla, etc.) for CMS-specific vulnerability checks.

- 🛡️ **Security Header Analysis**  
  • Checks for important HTTP security headers such as:
    - `Strict-Transport-Security`
    - `X-Content-Type-Options`
    - `X-Frame-Options`
    - And more.

- 🧱 **WAF (Web Application Firewall) Detection**  
  • Attempts to detect the presence of a WAF protecting the application.

---

## 📥 Installation

**Requirements**  
- Python 3.x
- `requests`, `socket`, and other supporting libraries.

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

After launching, you'll be greeted with an interactive menu:

```plaintext
Welcome to WASTT - Web Application Security Testing Tool!

Choose an option:
[1] Test for SQL Injection
[2] Test for XSS (Cross-Site Scripting)
[3] Directory Brute Force
[4] Detect CMS (WordPress, Joomla, etc.)
[5] Check for Security Headers
[6] Detect WAF (Web Application Firewall)
[7] Exit
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
