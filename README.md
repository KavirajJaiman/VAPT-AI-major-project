# 🔐 VAPT-AI

**AI-Powered Vulnerability Assessment & Penetration Testing Tool**

---

## 📌 Overview

VAPT-AI is a cybersecurity project that automates **Vulnerability Assessment and Penetration Testing (VAPT)** using AI-driven analysis.

It performs reconnaissance, scans for vulnerabilities, and provides intelligent insights, remediation suggestions, and reports through an interactive web interface.

---

## 🎯 Key Features

* 🔍 Automated vulnerability scanning
* 🌐 Reconnaissance (WHOIS, DNS, SSL, technology detection)
* ⚡ Port & service scanning (Nmap integration)
* 🤖 AI-powered vulnerability analysis
* 💬 AI chatbot for security assistance
* 📄 PDF report generation
* 🛠️ Utility tools (hashing, encoding, basic parsing)

---

## 🧠 My Contribution

* Built backend scanning and analysis modules
* Integrated AI for vulnerability insights and remediation
* Developed frontend dashboard using React
* Implemented API endpoints and report generation
* Designed overall system architecture

---

## 🏗️ Tech Stack

**Backend:** Python, Flask, SQLite
**Frontend:** React (Vite), Axios, Recharts
**AI:** Google Generative AI (Gemini API)

---

## 📁 Project Structure

```bash
backend/        # Flask backend
frontend/       # React frontend
Dockerfile
requirements.txt
netlify.toml
render.yaml
```

---

## ⚙️ Installation & Setup

### 🔹 Clone Repository

```bash
git clone https://github.com/KavirajJaiman/VAPT-AI-major-project.git
cd VAPT-AI-major-project
```

---

### 🔹 Backend Setup

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate

pip install -r requirements.txt
```

---

### 🔹 Configure Environment

Create `.env` inside `backend/`:

```
GEMINI_API_KEY=your_api_key_here
GEMINI_MODEL=gemini-2.5-flash
```

---

### 🔹 Run Backend

```bash
cd backend
python app.py
```

---

### 🔹 Run Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🚀 Usage

1. Start backend server
2. Run frontend application
3. Open browser and access the dashboard
4. Enter target for scanning
5. View vulnerabilities, AI insights, and reports

---

## 📊 Output

* Vulnerability scan results
* AI-based analysis
* Security recommendations
* Downloadable PDF reports

---

## ⚠️ Important Notes

* Install **Nmap** for full scanning functionality
* AI features require a valid API key
* Do not commit real API keys
* Some features may be limited without external tools

---

## 🛡️ Security Disclaimer

This project is for **educational purposes only**.
Do not use it on systems without proper authorization.

---

## 👨‍💻 Author

**Kaviraj Sharma**
BCA (Cyber Security Student)

---

## ⭐ Acknowledgment

Inspired by modern cybersecurity tools and AI-based security research.
