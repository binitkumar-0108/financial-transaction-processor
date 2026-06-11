# Financial Transaction Processor

## Overview
This project simulates a real-time transaction processing system using Spring Boot and Apache Kafka.

It processes financial transactions asynchronously and calculates incentives based on business logic.

## Architecture
- Producer sends transaction events
- Kafka handles message queue
- Consumer processes transactions
- Incentives are calculated and stored

## Tech Stack
- Java 17
- Spring Boot
- Apache Kafka
- Maven

## Features
- Event-driven architecture
- Real-time transaction processing
- Incentive calculation system
- REST API endpoints

## How It Works
1. Transaction is created
2. Sent to Kafka topic
3. Consumer listens and processes it
4. Incentive is calculated
5. Data is stored

## Note
Inspired by JP Morgan Software Engineering Virtual Experience (Forage)
