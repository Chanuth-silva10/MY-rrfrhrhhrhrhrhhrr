# Microservices-Based Backend for simple E-Commerce Platforms with deep tech stack
SmartCart is a scalable, cloud-native e-commerce backend system designed using modern microservices architecture. It leverages key technologies like Spring Boot, Kafka, Docker, Kubernetes, Resilience4J, and observability tools (Prometheus, Grafana, OpenTelemetry) to ensure high resilience, fault tolerance, and efficient communication between services. The project focuses on backend engineering, integrating MongoDB and MySQL for data storage, and emphasizes self-study to explore technologies beyond typical industry projects

## Services Overview

- Product Service
- Order Service
- Inventory Service
- Notification Service
- API Gateway using Spring Cloud Gateway MVC
- Shop Frontend using Angular 18

## Tech Stack

The technologies used in this project are:

- Spring Boot
- Angular
- MongoDB
- MySQL
- Kafka
- Keycloak
- Test Containers with Wiremock
- Grafana Stack (Prometheus, Grafana, Loki and Tempo)
- API Gateway using Spring Cloud Gateway MVC


## Application Architecture
![image](https://github.com/user-attachments/assets/d4ef38bd-8ae5-4cc7-9ac5-7a8e5ec3c969)

## Grafana Dashoard
![Grafana Dashboard for each service](https://github.com/user-attachments/assets/35d47fb2-7145-4eff-8529-1d8d1eba9f1b)

## Add Product UI
![Add Product UI](https://github.com/user-attachments/assets/2cd8d544-24e2-4639-a2dd-275b9ff37146)

## Place Order UI
![Place Order UI](https://github.com/user-attachments/assets/22c19800-cce1-4d1b-84ba-34a4971a9eb7)

## API Gateway Service with Prometheus
![api gateway service with promethues](https://github.com/user-attachments/assets/9377b146-6b4d-4723-b0f3-071e09feec5c)

## API Gateway with Loki
![api gateway with loki](https://github.com/user-attachments/assets/7c5d6cd2-dde2-4bf3-85ef-63207d259aac)

## Check Email
![Check Email](https://github.com/user-attachments/assets/b724f0c7-ed7f-446f-805c-dd8c3140036f)

## Kafka Consumer
![Kafka Consumer](https://github.com/user-attachments/assets/c9b276e6-422b-4cac-a869-6f8899111b2d)

## Kafka Sending message
![Kafka Sending message](https://github.com/user-attachments/assets/8b8fc9fe-b34e-4be5-8311-d75b2087ab3e)

## Kafka Topic
![Kafka Topic](https://github.com/user-attachments/assets/eb99299a-4382-44b6-b5eb-d021dc4644f5)

## Microservice Docker Containers
![Microservice Docker Containers](https://github.com/user-attachments/assets/a99b85c7-5313-4b08-a453-92a45daf777b)

## How to run the frontend application

Make sure you have the following installed on your machine:

- Node.js
- NPM
- Angular CLI

Run the following commands to start the frontend application

```shell
cd frontend
npm install
npm run start
```
## How to build the backend services

Run the following command to build and package the backend services into a each docker container

```shell
docker compose up -d
```
