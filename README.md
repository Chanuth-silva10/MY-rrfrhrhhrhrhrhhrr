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
