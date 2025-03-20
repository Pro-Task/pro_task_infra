# Infrastructure Repository

This repository contains the infrastructure configuration files for the **Pro Task Platform**. It includes configurations for:
- **Docker Compose** setup for all microservices
- **Nginx** as API Gateway
- **Kafka** for event-driven messaging  
- **Redis** for caching
- **PostgreSQL** as the main database  
- **ELK Stack** for logging and monitoring  

## Getting Started

1. **Clone this repository**  
   ```sh
   git clone https://github.com/Pro-Task/infra.git
   cd infra
2. **Ensure you have Docker & Docker Compose installed**
    Download from https://www.docker.com/
3.**Start the infrastructure**
    ```sh
    docker-compose up -d
