# Flask Tutorial

## Run Without Container

### Set up Virtual Environment

`python3 -m venv .venv`

`. .venv/bin/activate`

### Install dependencies

`pip install -e .`

## Run with Container

`docker stop flaskr && docker rm flaskr && docker build -t latest . && docker run --name flaskr -p 8080:8080 -p 5000:5000 latest`
