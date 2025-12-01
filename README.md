# Flask App - Dockerized & Deployed

A simple Flask web application containerized with Docker and deployed on CapRover.

## 🚀 Live Demo

**Deployed App:** https://flask-app-1.dev.killiandelamarre.dev

**Status Page:** [Your UptimeRobot URL here]

## 📊 Badges

![Uptime Status](https://img.shields.io/uptimerobot/status/YOUR_MONITOR_ID)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fflask-app-1.dev.killiandelamarre.dev)

## 🐳 How to Build and Run

### Prerequisites
- Docker installed
- Docker Compose installed

### Build and Run Locally

1. Clone the repository:
```bash
git clone git@github.com:KJSDR/ACS3220-Dockerized-App.git
cd git@github.com:KJSDR/ACS3220-Dockerized-App.git
```

2. Build and run with Docker Compose:
```bash
docker-compose up
```

3. Visit `http://localhost:5001` in your browser

### Stop the Application
```bash
docker-compose down
```

## 📁 Project Structure

- `Dockerfile` - Docker configuration for the Flask app
- `docker-compose.yml` - Multi-container setup with database
- `app.py` - Main Flask application
- `requirements.txt` - Python dependencies

## 🌐 Deployment

Deployed on CapRover at `dev.killiandelamarre.dev`

Monitored by UptimeRobot for 24/7 uptime tracking.