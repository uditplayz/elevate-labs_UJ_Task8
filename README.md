# Docker Cloud Deployment Task

## What This Container Does

This Docker container packages a Flask web application with Python runtime and all dependencies into a portable, isolated environment. The containerization ensures the application runs identically on any platform—from local development to cloud production—eliminating environment inconsistencies. When deployed to Google Cloud Run, the container automatically scales based on incoming traffic, spinning up instances when needed and scaling to zero during idle periods to optimize costs. This demonstrates modern cloud-native deployment: applications are built once as immutable containers and deployed anywhere with consistent behavior and minimal infrastructure management.

## Screenshots

<img width="1920" height="1080" alt="localhost" src="https://github.com/user-attachments/assets/12dd01c0-1f92-4e5b-bf17-a0c9b4b36903" />

<img width="1920" height="1080" alt="live-on-gcp" src="https://github.com/user-attachments/assets/1d113183-8687-452b-b1c7-eec64837de90" />

<img width="1920" height="1080" alt="cloud-run" src="https://github.com/user-attachments/assets/4c8df368-853f-406e-a583-764c02f0fadc" />

<img width="1920" height="1080" alt="docker-images" src="https://github.com/user-attachments/assets/0918a5da-0bb9-4289-957e-15ece33f6d33" />


---

## Files
- `app.py` - Flask application
- `Dockerfile` - Container configuration
- `requirements.txt` - Python dependencies

Date: October 31, 2025
