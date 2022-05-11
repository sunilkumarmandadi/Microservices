
## Micro services project

### In this project I have used the following technologies

**1. Catalog microservice module includes**
   - ASP.NET Core Web API application
   - MongoDB database 
   - Containerization using **Docker**
   - Repository Pattern Implementation
   - Swagger Open API implementation
   
**2. Basket microservice module includes**

- Redis database
- Containerization using **Docker**
- Consume Discount Grpc Service for inter-service sync communication to calculate product final price
Publish BasketCheckout Queue with using MassTransit and RabbitMQ

**3. Discount microservice module includes**

- ASP.NET Grpc Server application
- gRPC Communication 
- Dapper micro-orm implementation to simplify data access and ensure high performance
- PostgreSQL database 
- Containerization using **Docker**
