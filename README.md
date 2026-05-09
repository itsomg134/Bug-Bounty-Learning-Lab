#  Bug Bounty Learning Lab

> A practical, educational repository for learning web application security and responsible bug hunting.

** Disclaimer:** This repository is for **educational purposes only**. All security testing should be performed only on systems you own or have explicit written permission to test. Unauthorized hacking is illegal.

##  Table of Contents

- [About](#about)
-  Features
-  Vulnerabilities Covered
-  Getting Started
-  Tools Used
-  Learning Resources
-  Responsible Disclosure
-  License

##  About

This repository serves as my personal lab and knowledge base for learning ethical hacking, web security, and bug bounty hunting. All examples and exercises are designed to be run in isolated, authorized environments such as local virtual machines or legal training platforms.

##  Features

-  Interactive XSS demo (safe, local-only)
-  SQL injection simulation lab
-  Bug bounty checklist and methodology notes
-  OWASP Top 10 practical examples
-  Progress tracker for bug bounty programs

##  Vulnerabilities Covered

| Vulnerability | OWASP Category |
|---------------|----------------|--------|
| Cross-Site Scripting (XSS) | A03:2021 – Injection |
| SQL Injection | A03:2021 – Injection |
| CSRF | A04:2021 – Insecure Design |
| Broken Access Control | A01:2021 |
| SSRF | A10:2021 – SSRF |

##  Getting Started

### Prerequisites

- Modern web browser (Chrome/Firefox)
- Local web server (Python, Node.js, or XAMPP)
- Burp Suite Community Edition (recommended)

### Clone the Repository

```bash
git clone https://github.com/yourusername/bug-bounty-learning-lab.git
cd bug-bounty-learning-lab
```

### Run Locally (Safe Practice)

```bash
# Using Python's built-in HTTP server
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

> **Important:** Never upload this to a public web server. Use only on `localhost` or within an isolated virtual machine.

##  Tools I'm Learning

| Tool | Purpose |
|------|---------|
| Burp Suite | Web traffic interception & testing |
| OWASP ZAP | Automated vulnerability scanning |
| Nmap | Network reconnaissance |
| SQLmap | SQL injection automation (authorized only) |
| ffuf | Directory and parameter fuzzing |

##  Learning Resources

| Resource | Type | Link |
|----------|------|------|
| PortSwigger Web Security Academy | Free Labs | [portswigger.net/web-security](https://portswigger.net/web-security) |
| OWASP Top 10 | Documentation | [owasp.org/Top10](https://owasp.org/Top10) |
| Hacker101 | Free Videos & Challenges | [hacker101.com](https://www.hacker101.com) |
| Hack The Box (Academy) | Hands-on | [academy.hackthebox.com](https://academy.hackthebox.com) |
| PentesterLab | Exercises | [pentesterlab.com](https://pentesterlab.com) |

##  Responsible Disclosure – My Process

1. **Identify** vulnerability on an authorized bug bounty program (HackerOne, Bugcrowd, etc.)
2. **Document** reproducible steps with screenshots
3. **Report** privately via the company's security contact or platform
4. **Wait** for triage and response – never exploit beyond PoC
5. **Coordinate** public disclosure timeline (if any) with the vendor

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
