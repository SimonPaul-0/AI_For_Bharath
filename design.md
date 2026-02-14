# System Design – SevaSetu

## High Level Architecture
Client -> Load Balancer -> API Server -> Services -> Database

## Major Components
- Authentication Service
- Scheme Recommendation Engine
- Application Processor
- Notification Service

## Database
Users
Schemes
Applications
Documents

## Scalability
- Stateless APIs
- Horizontal scaling
- Caching popular schemes
- Queue for heavy processing

## Security
- JWT based authentication
- Encrypted data storage
