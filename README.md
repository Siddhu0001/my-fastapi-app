
# My FastAPI App 🚀

A simple FastAPI application with automated CI/CD pipeline using GitHub Actions and Render.

## Features
- FastAPI REST API
- Auto testing with pytest
- Auto deploy to Render on every push to main

## Local Setup

### 1. Install dependencies
pip install -r requirements.txt

### 2. Run the app
uvicorn app.main:app --reload

### 3. Run tests
pytest tests/ -v

## API Endpoints

| Method | Endpoint  | Description        |
|--------|-----------|--------------------|
| GET    | /         | Hello World        |
| GET    | /health   | Health Check       |

## CI/CD Flow

Push code → GitHub Actions runs tests → Tests pass → Auto deploy to Render

## Live URL
https://your-app-name.onrender.com