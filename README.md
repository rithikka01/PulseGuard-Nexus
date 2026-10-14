# PulseGuard Nexus — Industrial IoT Command Center

PulseGuard Nexus is a Flask-based web application designed to provide a centralized dashboard for monitoring industrial IoT assets, alerts, system status, maintenance, and anomaly information.

## Features

- Industrial IoT monitoring dashboard
- Asset inventory management interface
- Alerts and anomaly monitoring
- Maintenance and claims API endpoints
- SQLite database integration
- AI-powered analysis integration using Groq

## Tech Stack

- **Backend:** Python, Flask, Flask-CORS
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite
- **System monitoring:** psutil
- **AI integration:** Groq API

## Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/rithikka01/PulseGuard-Nexus.git
   cd PulseGuard-Nexus
   ```

2. Create and activate a virtual environment, then install dependencies:
   ```bash
   python -m venv .venv
   ```

   Windows:
   ```bash
   .venv\Scripts\activate
   ```

   Install packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Start the application:
   ```bash
   python app.py
   ```

4. Open `http://127.0.0.1:8080` in your browser.

## Configuration

Set any required API keys as environment variables. Do not commit secrets to GitHub.

## Project Status

Local application running; public deployment pending.
