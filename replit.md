# Flask Learning Website

## Overview
This is a Flask learning project that demonstrates basic web development with Python. The project was imported from GitHub and configured to run in the Replit environment.

## Project Architecture
- **Backend**: Flask web framework (Python)
- **Frontend**: HTML templates with Jinja2 templating
- **Styling**: CSS embedded in base template
- **Server**: Development server (Flask) / Production server (Gunicorn)

## Key Files
- `app.py` - Main Flask application with routes
- `templates/` - HTML templates directory
  - `base.html` - Base template with navigation
  - `index.html` - Home page template
  - `about.html` - About page template
- `requirements.txt` - Python dependencies
- `.replit` - Replit configuration

## Features
- Template inheritance with Jinja2
- Multiple routes (/, /about)
- Responsive design
- Configured for Replit environment (0.0.0.0:5000)
- Production-ready deployment with Gunicorn

## Development Setup
- Python 3.11 installed
- Flask development server runs on port 5000
- Debug mode enabled for development
- All hosts allowed for Replit proxy support

## Recent Changes
- 2025-09-08: Initial setup and configuration for Replit environment
- Added basic Flask application structure
- Configured deployment settings with Gunicorn
- Set up workflow for development server