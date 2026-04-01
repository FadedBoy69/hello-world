# Hello World

A simple static Hello World web app deployed with Docker, GitHub Actions CI, and cloud CD platforms.

## Stack
- HTML
- Docker
- Nginx
- GitHub Actions
- Render
- Railway

## Live URL
- Render: https://hello-world-pqy8.onrender.com
- Railway: https://hello-world-production-4f47.up.railway.app/

## Features
- Static web page served by Nginx
- Dockerized deployment
- CI with GitHub Actions
- Continuous deployment from GitHub
- Deployable to multiple cloud platforms

## Architecture
Source code is stored in GitHub.
GitHub Actions runs a Docker build on each push to `main`.
Render and Railway can both deploy the latest version from the GitHub repository and serve the site publicly using Docker and Nginx

Pipeline:
Local Code → GitHub → GitHub Actions CI → Render / Railway CD → Public Website