# 🔍 Phishing Link Detector

This is a simple web application that helps identify potentially dangerous (phishing) URLs using client-side JavaScript. It is designed to provide basic protection by highlighting suspicious characteristics in a URL.

---

## 🧠 How It Works

Phishing websites often use tricky or misleading URLs to fool users into giving away sensitive information like login credentials or personal details. This tool analyzes URLs for common red flags using simple heuristics:

### 🔐 Detection Heuristics:

- **IP Address in URL**: Legitimate websites rarely use direct IP addresses in links. URLs like `http://192.168.0.1/login` are considered suspicious.
  
- **Presence of '@' Symbol**: In URLs, the `@` symbol can be used to obscure the actual target address. For example: `http://example.com@phishy-site.com`.
  
- **Suspicious Keywords**: Words like `login`, `secure`, `update`, `free`, `account`, or `confirm` are often used to scare or trick users into clicking.
  
- **Excessive Length**: Very long URLs can be used to hide the real destination and confuse users.

Each of these characteristics adds to a risk score. If the score crosses a threshold (e.g., 2 or more red flags), the link is labeled as potentially phishing.

---

## 🛠️ Technologies Used

- **HTML5**: For structuring the webpage
- **CSS3**: For styling the user interface
- **Vanilla JavaScript (ES6)**: For detecting phishing characteristics on the client side

---

## 💡 Use Case

- Can be used by individuals to quickly check if a link looks suspicious
- Useful in educational settings to demonstrate basic phishing patterns
- Can be integrated into internal tools to pre-screen URLs

---

## 📌 How to Run

1. Download or clone the project folder.
2. Open the `index.html` file in your web browser.
3. Enter any URL in the input box and click the **Check URL** button.
4. The app will display whether the link is likely **SAFE ✅** or **PHISHING ⚠️** based on the simple checks.

> No installation or server setup is required — it's a fully static web page.

---

## ⚠️ Disclaimer

This tool is intended for **educational** or **demonstration purposes** only. It uses basic logic and cannot replace professional anti-phishing systems or databases. Always use caution and verify links through secure sources.

---

## 👨‍💻 Author

This project was created to illustrate simple front-end security logic. You are free to modify or expand it for your needs.
