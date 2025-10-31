# 🔐 Password Security Toolkit

A comprehensive web-based cybersecurity tool that helps users evaluate password strength and generate SHA-256 cryptographic hashes. Built with vanilla HTML, CSS, and JavaScript for maximum portability and ease of use.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Overview

This project provides two essential cybersecurity tools in a single, easy-to-use web interface:

1. **Password Strength Checker** - Analyzes passwords in real-time and provides detailed feedback on their security level
2. **SHA-256 Hash Generator** - Generates secure SHA-256 cryptographic hashes for any text input

Perfect for security awareness training, password policy implementation, or as a learning resource for understanding cryptographic concepts.

## ✨ Features

### Password Strength Checker
- **Real-time Analysis** - Instant feedback as users type
- **Comprehensive Evaluation** - Checks for:
  - Minimum length requirements
  - Uppercase and lowercase letters
  - Numbers and special characters
  - Common password patterns
- **Visual Indicators** - Color-coded strength meter (Weak/Medium/Strong)
- **Security Recommendations** - Actionable tips to improve password strength
- **Client-side Processing** - Passwords never leave your browser

### SHA-256 Hash Generator
- **Secure Hashing** - Industry-standard SHA-256 algorithm
- **Instant Generation** - Real-time hash calculation
- **Copy to Clipboard** - One-click hash copying
- **Multiple Use Cases** - Perfect for:
  - Data integrity verification
  - Password hashing demonstrations
  - Checksum generation
  - Educational purposes

## 🚀 [Demo](https://yashpatil118.github.io/password-security-toolkit/)


## 📸 Screenshots


```
pow1.png
pow2.png
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling and responsive design
- **JavaScript (ES6+)** - Client-side logic and cryptographic operations
- **Web Crypto API** - Native SHA-256 hash generation

## 📦 Installation & Usage

### Option 1: Direct Download
1. Clone this repository:
```bash
git clone https://github.com/yourusername/password-security-toolkit.git
```

2. Navigate to the project directory:
```bash
cd password-security-toolkit
```

3. Open `index.html` in your web browser

### Option 2: GitHub Pages
Simply visit the live demo link above - no installation required!

### Option 3: Local Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server
```
Then navigate to `http://localhost:8000`

## 💻 Project Structure

```
password-security-toolkit/
│
├── index.html          # Main HTML file with embedded CSS and JS
├── password.html       # password strength checking page
├── hash.html           # web page for hash generation
├── contact.html        # contact form page
├── README.md           # Project documentation
└── LICENSE             # License file (optional)
```

## 🔒 Security Features

- **No Data Transmission** - All operations are performed locally in the browser
- **No External Dependencies** - Uses native Web APIs for security operations
- **Privacy-Focused** - Passwords and text are never stored or transmitted
- **Open Source** - Transparent code for security auditing

## 🎯 Password Strength Criteria

The tool evaluates passwords based on the following criteria:

| Strength Level | Requirements |
|----------------|--------------|
| **Weak** | Less than 8 characters or missing multiple character types |
| **Medium** | 8+ characters with some character variety |
| **Strong** | 12+ characters with uppercase, lowercase, numbers, and special characters |

## 🧪 Use Cases

- **Educational Tool** - Learn about password security and cryptographic hashing
- **Security Training** - Demonstrate password best practices to teams
- **Development** - Quick hash generation for testing purposes
- **Personal Security** - Evaluate and improve your own passwords
- **Data Integrity** - Generate checksums for file verification

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contribution
- Add password generation feature
- Implement additional hash algorithms (MD5, SHA-512)
- Add multi-language support
- Improve UI/UX design
- Add password breach checking (using Have I Been Pwned API)
- Create password history/manager functionality

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is designed for educational and personal use. While it provides helpful guidance on password security, always follow your organization's specific security policies and use a dedicated password manager for storing sensitive credentials.

## 👨‍💻 Author

**Yash Patil**
- GitHub: [@yashpatil118](https://github.com/yashpatil118)
- LinkedIn: [follow](https://www.linkedin.com/in/yash-patil-069820252/)

## 🙏 Acknowledgments

- Built with JavaScript 
- SHA-256 implementation using Web Crypto API
- Inspired by modern cybersecurity best practices

## 📚 Learn More

- [OWASP Password Storage Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
- [NIST Password Guidelines](https://pages.nist.gov/800-63-3/sp800-63b.html)
- [SHA-256 Wikipedia](https://en.wikipedia.org/wiki/SHA-2)

---

⭐ **Star this repository if you find it helpful!**

*Made with 🔐 for better cybersecurity*
