# Analytics Service

## Overview
Analytics Service is a backend application designed for collecting, processing, and analyzing data. It provides APIs for tracking user behavior, generating insights, and managing analytical reports to support decision-making processes.

## Features
- **Data Tracking:** Collect and store user activity and other analytical data.
- **Data Aggregation:** Process large datasets to generate meaningful insights.
- **Report Generation:** Create custom analytical reports.
- **Real-Time Analytics:** Support for near real-time data processing.
- **Swagger Documentation:** Provides detailed API documentation for integration.

## Getting Started

### Prerequisites
- Java 17
- Docker (optional for containerized deployment)
- Gradle

### Steps
1. Clone the repository:
   
   git clone https://github.com/IvanMatiko/analytics_service.git
   cd analytics_service

2. Build the project: ./gradlew build

3. Run the application: ./gradlew bootRun

# API Endpoints
POST /analytics/events: Submit a new analytics event.

GET /analytics/reports: Retrieve a list of available reports.

GET /analytics/reports/{id}: Get detailed information for a specific report.

DELETE /analytics/data: Clear stored analytical data.

# Technologies Used

Java: Core programming language.

Spring Boot: Framework for building backend services.

Gradle: Build and dependency management tool.

Swagger: API documentation tool.

Docker: For containerized deployments.

Postgres: SQL database

Redis: cache and message broker


   
