# My Docker Project

This is a simple Dockerized static website project.

## Project Description

This project demonstrates how to serve a static `index.html` page using Docker and Nginx.

## Files Included

- `Dockerfile`: Docker configuration file to build the container image.
- `index.html`: Simple static HTML page served by Nginx.
- `README.md`: Project documentation.

## How to Build and Run

1. Build the Docker image:

    ```bash
    docker build -t my-docker-project .
    ```

2. Run the Docker container:

    ```bash
    docker run -d -p 8080:80 my-docker-project
    ```

3. Open your browser and go to: `http://localhost:8080`

You should see your static website.

## Author

Nagaraj
