# Python Web Application with Docker and Nginx

This is a base Python web application that displays "Hello, World!" on the home page, configured with Docker using Nginx as a reverse proxy.

## Features
- Python Flask web application
- Docker configuration
- Nginx reverse proxy setup
- Docker Compose orchestration

## Getting Started

### Prerequisites
- Docker and Docker Compose installed

### Running the Application
1. Build and start the containers:
   ```bash
   docker-compose up --build
   ```

2. Access the application at:
   ```
   http://localhost
   ```

### Project Structure
- `app.py` - Main Python Flask application
- `requirements.txt` - Python dependencies
- `Dockerfile` - Docker configuration for the Python app
- `nginx.conf` - Nginx reverse proxy configuration
- `docker-compose.yml` - Docker Compose orchestration file

## Deployment
The application is configured to run with:
- Python 3.11 slim image
- Gunicorn as WSGI server
- Nginx as reverse proxy on port 80