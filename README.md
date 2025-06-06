# DVWA Docker Lab - SQL Injection Educational Environment

This project sets up the Damn Vulnerable Web Application (DVWA) using Docker, aimed at practicing SQL Injection attacks in a safe, isolated environment.

---
---

## 🚨 Legal Disclaimer

**This project is intended for ethical educational purposes only. Any misuse of the contents is solely the responsibility of the user.**

- ⚠️ Do not use this project on systems you do not own.
- ⚠️ Do not expose this environment to the public internet.
- ⚠️ Use only in local or private testing environments.
- ❌ Never use this knowledge for illegal or malicious activities.

✅ This project complies with ethical hacking principles and GitHub's Terms of Service.

## ⚠️ Important Notice

This environment is intended *only for educational and ethical purposes*.  
Do NOT use these techniques on any system without explicit permission. Unauthorized testing or exploitation is illegal and unethical.

---

##  Requirements

- Docker Desktop installed and running  
- WSL 2 enabled on Windows (for Windows users)  
- Basic knowledge of Docker commands

---

##  Setup Instructions

1. Clone this repository:  
   ```bash
   git clone https://github.com/franciscoprimo/sql-injection-dvwa-docker
   cd sql-injection-dvwa-docker/dvwa

	2.	Start the DVWA container:

docker compose up -d


	3.	Open your browser and visit:
http://localhost:8080
	4.	Login with default credentials:
	•	Username: admin
	•	Password: password
	5.	Click Create / Reset Database to initialize the app.
	6.	Set DVWA Security level to Low for vulnerable testing.

⸻

💡 Testing SQL Injection
	•	Navigate to the SQL Injection section in DVWA.
	•	Enter the payload:

1' OR '1'='1


	•	Submit and observe how the application returns all records, demonstrating the SQL Injection vulnerability.

⸻

⚠️ DISCLAIMER:
This project is for educational purposes only. We are not responsible for any misuse of the techniques demonstrated here. Use only in test environments under your own responsibility.
