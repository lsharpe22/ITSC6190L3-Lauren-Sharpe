# ITSC 6190 Lab 3

A simple Flask application containerized using Docker.

## How to Run

Build the Docker image:

```bash
docker build -t flask-app .
```

Run the application:

```bash
docker run -p 5000:5000 flask-app
```

Then open `http://localhost:5000` in your browser.
