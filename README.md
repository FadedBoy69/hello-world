# Hello World

A simple static Hello World web app deployed with Docker, GitHub Actions CI, and Render CD.

## Stack
- HTML
- Docker
- Nginx
- GitHub Actions
- Render

## Live URL
https://hello-world-pqy8.onrender.com

## Features
- Static web page served by Nginx
- Dockerized deployment
- CI with GitHub Actions
- Continuous deployment to Render

## Architecture
Source code is stored in GitHub.  
GitHub Actions runs a Docker build on each push to `main`.  
Render automatically deploys the latest version from the GitHub repository and serves the site publicly using Docker and Nginx.
Local Code → GitHub → GitHub Actions CI → Render CD → Public Website