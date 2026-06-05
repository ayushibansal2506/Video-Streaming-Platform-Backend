# Video Streaming Platform Backend

A scalable backend platform designed for subscription-based video streaming services. The application follows a microservices architecture and supports video management, user authentication, subscription handling, payment processing, and content delivery workflows.

The platform integrates with Stripe for subscription payments and automates subscription lifecycle management, including renewal, cancellation, and status tracking. The system is designed to handle large-scale video content while maintaining reliability, scalability, and performance.

## Features

* User authentication and authorization
* Video upload and metadata management
* Subscription-based access control
* Stripe payment gateway integration
* Automated subscription renewal workflows
* Subscription cancellation and status management
* Content storage and retrieval
* Scalable microservices architecture
* RESTful API design
* Containerized deployment support

## Tech Stack

### Backend

* Go (Golang)
* REST APIs

### Database & Storage

* PostgreSQL
* Redis
* Amazon S3

### Infrastructure

* Docker
* Kubernetes

### Integrations

* Stripe Payment Gateway

## Architecture

```text
Users
   │
   ▼
API Gateway
   │
 ┌─┴───────────────┐
 ▼                 ▼
User Service   Subscription Service
                    │
                    ▼
                Stripe API
                    │
                    ▼
             Payment Processing

Video Service
     │
     ▼
 Amazon S3 Storage

PostgreSQL + Redis
```

## Key Learning Outcomes

* Microservices architecture design
* Payment gateway integration with Stripe
* Subscription lifecycle management
* Distributed backend system development
* Object storage management using Amazon S3
* Caching strategies with Redis
* Container orchestration using Kubernetes
* Scalable REST API development

