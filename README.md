# Hello World FastAPI Docker Example

This is a minimal FastAPI API that returns a JSON hello message. It is ready to be deployed with Docker and hosted on GitHub.

## Quickstart

1. **Run locally**
   ```sh
   pip install -r requirements.txt
   uvicorn main:app --reload
   ```
   Visit http://127.0.0.1:8000

2. **Build and run with Docker**
   ```sh
   docker build -t hello-api .
   docker run -p 8000:8000 hello-api
   ```
   Visit http://localhost:8000

## Endpoints
- `/` : Returns `{ "message": "Hello, World!" }`

## Deploy to GitHub
- Push this folder to a new GitHub repository.
