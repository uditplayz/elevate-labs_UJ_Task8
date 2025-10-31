# Docker Cloud Deployment Task

## What This Container Does

This Docker container packages a Flask web application with Python runtime and all dependencies into a portable, isolated environment. The containerization ensures the application runs identically on any platform—from local development to cloud production—eliminating environment inconsistencies. When deployed to Google Cloud Run, the container automatically scales based on incoming traffic, spinning up instances when needed and scaling to zero during idle periods to optimize costs. This demonstrates modern cloud-native deployment: applications are built once as immutable containers and deployed anywhere with consistent behavior and minimal infrastructure management.

## Screenshots

### Local Docker Container Running
![Local Container]()

### Docker Images List  
![Docker Images]()

### Google Cloud Run Live URL
![Live Deployment]()

---

## Files
- `app.py` - Flask application
- `Dockerfile` - Container configuration
- `requirements.txt` - Python dependencies

Date: October 31, 2025
