# JP Morgan Virtual Experience Project

## Overview
Built a transaction processing system using Spring Boot and Kafka.

## Features
- Event-driven architecture using Kafka
- Real-time incentive calculation
- REST APIs for transaction handling

## Tech Stack
- Java 17
- Spring Boot
- Apache Kafka

## How to Run
1. Clone the repository
   git clone https://github.com/your-username/your-repo-name.git

2. Navigate to project folder
   cd your-repo-name

3. Start Kafka and Zookeeper
   (Make sure Kafka is running on localhost:9092)

4. Build the project
   ./mvnw clean install

5. Run the Spring Boot application
   ./mvnw spring-boot:run

6. Test APIs
   Use Postman or curl to send requests to:
   http://localhost:8080

## Project Explanation

This project simulates a transaction processing system using an event-driven architecture.

Transactions are produced and sent to a Kafka topic. A Kafka consumer listens to these events, processes each transaction, and calculates incentives based on predefined business logic.

The system uses Spring Boot for building REST APIs and handling backend operations. The architecture ensures scalability and real-time processing of financial data.