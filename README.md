# Apache Airflow

This repository contains a Docker Compose file capable of deploying an Apache Airflow instance
and all its components.

Additionally, a DAG is provided for testing purposes.

## Running the project
Add your user ID to the .env file:

    echo -e "AIRFLOW_UID=$(id -u)" > .env

Run Docker Compose on the project root folder to bring the environment up:

    docker compose up

## Accessing the web interface
Access http://localhost:8080 on your browser.
