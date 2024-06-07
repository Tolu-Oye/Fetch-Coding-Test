# Fetch-Coding-Test

# Receipt Processor

This is a Spring Boot application for processing receipts and calculating points based on defined rules.

## Prerequisites

- Docker
- Docker Compose

## How to Run the Application

1. **Clone the repository** to your local machine.
2. **Use Docker Compose** to build the Docker image and run the container with `docker-compose up --build`.

cd receiptprocessor
docker-compose up --build
  
4. **Access the application** via `http://localhost:8080` using Postman or any other HTTP client

Access the application:

Once the container is running, you can access the application using the following endpoints:

Process Receipt:
URL: http://localhost:8080/receipts/process
Method: POST
Body: JSON payload


Get Points:
URL: http://localhost:8080/receipts/{id}/points
Method: GET
Replace {id} with the actual receipt ID returned from the POST /receipts/process endpoint.

