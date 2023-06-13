# PhotoApp_microservice
This repository contains the code for the PhotoAppAPIConfigServer microservice project. It is a part of a larger system of microservices designed for a photo application.

## Description
The PhotoAppAPIConfigServer microservice is responsible for managing the configuration of other microservices in the system. It utilizes the Spring Cloud Configuration Server to provide dynamic configuration broadcasting to the other microservices. This allows for easy configuration management and updates across the entire system.

## Features and Technologies Used
* Spring Cloud Configuration Server: Used to manage and distribute configurations to other microservices.
* Spring Cloud Bus: Employed for dynamic configuration broadcasting across microservices using RabbitMQ as the message broker.
* Spring Security and JWT: Implemented to ensure secure access to the Eureka Server UI.
* Netflix Feign Client: Facilitates effective load balancing and communication between microservices.
* Sleuth, Zipkin, and ELK Stack: Utilized for log tracing and monitoring microservices.
* Netflix Hystrix Library: Integrated into the API Gateway to handle failures of external services.
* Docker: Microservices are deployed in Docker containers to optimize caching and resource sharing.
* EC2 Linux Machines: Multiple EC2 Linux instances are used for running the Docker containers.

## Getting Started
To run the PhotoAppAPIConfigServer microservice locally, follow these steps:
1. Clone the repository to your local machine.
2. Install the necessary dependencies and libraries mentioned in the project.
3. Configure the RabbitMQ message broker for Spring Cloud Bus, if not already done.
4. Set up the necessary security configurations for Spring Security and JWT.
5. Make sure you have Docker installed on your machine.
6. Build the Docker image for the microservice.
7. Deploy the Docker container on an EC2 Linux machine.
