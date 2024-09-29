# Deploy Machine Learning model

## Introduction

This is a simple web application that predicts the species of an Iris flower based on its sepal and petal measurements using FastAPI, Streamlit and Docker.

## Features

- Predicts Iris flower species base on user input.
- Simple UI(Frontend) using Streamlit.
- Write API using FastAPI.

## Installation

Clone the repository: ```git clone https://github.com/ngothanhnam0910/Deployment-machine-learning-model.git```

## Usage
Run services with docker-compose: ```docker compose -f docker-compose.yaml up -d```

This command will start two services: frontend and backend.

- Open your web browser and go to <ins>http://localhost://8501</ins> to view the app and <ins>http://localhost:8000</ins> to view the API service up.

### Result Final
![Application]("image/deployment.png")
