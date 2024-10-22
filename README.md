## Project Title
Flask Application on Kubernetes with CI/CD

This project demonstrates a Flask web application containerized using Docker and deployed on a Kubernetes cluster.
It also includes a GitHub Actions CI/CD pipeline to automate the build and deployment process.

## Prerequisites
- Docker
- Kubernetes (Minikube for local dev)
- Helm
- Python 3.x
- GitHub Actions
- Minikube
- kubectl

## Installation
1. Clone the repository: `git clone https://github.com/username/repo.git`
2. Set up the virtual environment: 
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt

## Build the image
```bash
   docker build -t ghcr.io/username/repo:latest .
   docker push ghcr.io/username/repo:latest

## Running Locally
To run the Flask application locally:

```bash
flask run
