# ⚡ PulseGuard Nexus — Industrial IoT Command Center

**A Flask-based industrial IoT monitoring dashboard for asset management, system health, maintenance tracking, alerts, and anomaly monitoring.**

<p align="center">
  <a href="https://pulseguard-nexus.onrender.com">🚀 Live Demo</a> •
  <a href="https://github.com/rithikka01/PulseGuard-Nexus">💻 GitHub Repository</a>
</p>

---

## 📌 Overview

PulseGuard Nexus is a web-based Industrial IoT Command Center designed to bring asset monitoring and operational insights into a centralized dashboard. It combines a Python Flask backend, an interactive web interface, SQLite database integration, and an AI analysis integration using Groq.

## ✨ Features

- **Monitoring Dashboard** — View system status, uptime, and critical alert indicators.
- **Asset Inventory** — Access the industrial asset management interface.
- **Alert Management** — View and track critical alerts.
- **Anomaly Monitoring** — Access anomaly-related information through API endpoints.
- **Maintenance Tracking** — Maintenance-related API integration.
- **Claims Management** — Claims-related API integration.
- **AI-Powered Analysis** — Groq API integration for AI-assisted analysis.
- **Database Integration** — SQLite for local data storage.
- **Responsive Web Interface** — Dashboard built using HTML, CSS, and JavaScript.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Backend | Python, Flask, Flask-CORS |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite |
| AI Integration | Groq API |
| System Monitoring | psutil |
| HTTP Requests | Requests |
| Deployment | Render |
| Version Control | Git, GitHub |

## 🏗️ Architecture

```text
User
  │
  ▼
Web Dashboard
(HTML, CSS, JavaScript)
  │
  ▼
Flask Application
(Python, REST API)
  │
  ├── SQLite Database
  ├── System Monitoring
  └── Groq AI Integration
```

## 🚀 Live Demo

**Try the deployed application:**

👉 https://pulseguard-nexus.onrender.com

The application is hosted on Render. The free service may take some time to respond after periods of inactivity.

## 💻 Run Locally

### Prerequisites

- Python 3.10 or later
- Git
- pip

### 1. Clone the repository

```bash
git clone https://github.com/rithikka01/PulseGuard-Nexus.git
cd PulseGuard-Nexus
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

If your AI analysis feature requires a Groq API key, configure it as an environment variable. Never commit API keys or other secrets to GitHub.

### 5. Start the application

```bash
python app.py
```

Open the following URL in your browser:

```text
http://127.0.0.1:8080
```

## 📁 Project Structure

```text
PulseGuard-Nexus/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── presentation/
    └── project-presentation.pptx
```

The presentation folder is optional. Add it when your actual PowerPoint file is ready.

## ☁️ Deployment

The application is deployed on **Render** using Gunicorn as the WSGI server.

- **Build command:** `pip install -r requirements.txt`
- **Start command:** `gunicorn app:app --bind 0.0.0.0:$PORT`

## 🔒 Security Notes

- Keep API keys and credentials out of source control.
- Configure secrets through environment variables.
- Use persistent storage or a suitable production database when persistent data is required.
- Review database initialization logic before production deployment.

## 🔮 Future Enhancements

- Real-time IoT sensor integration.
- Enhanced asset health analytics.
- Interactive anomaly visualizations.
- Role-based authentication and access control.
- Persistent production database integration.
- Automated testing and monitoring.

## 👩‍💻 Author

**Rithikka N.**

- GitHub: [@rithikka01](https://github.com/rithikka01)
- LinkedIn: [Rithikka N.](https://www.linkedin.com/in/rithikka-n-7018a2257/)

---

⭐ If you find this project interesting, consider starring the repository!
