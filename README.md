# SignMeUp Authentication Service

## Overview
SignMeUp is an Authentication Service built using Node.js to streamline the integration process for developers. It offers Software-as-a-Service (SaaS) functionality that can be seamlessly integrated into any application. The service is designed for horizontal scalability, prioritizing performance and security. Key features include rate-limiting for improved performance and DDoS attack prevention, ID generation using Tweeter’s Snowflake approach, and password hashing with the SHA512 algorithm.

## Key Features
- **SaaS Integration**: SignMeUp simplifies the authentication process for developers, allowing direct integration into their applications.
- **Horizontal Scalability**: The service is designed to scale horizontally to handle increased loads efficiently.
- **Performance Optimization**: Rate-limiting is implemented to enhance performance and prevent potential DDoS attacks.
- **ID Generation**: Utilizes Tweeter’s Snowflake approach for ID generation, ensuring uniqueness and consistency in distributed databases.
- **Security**: Passwords are hashed using the SHA512 algorithm, enhancing security and protecting user data.
- **Multicore CPU Utilization**: Worker processes are generated to efficiently utilize multicore CPUs, distributing requests among processes.

## Technologies Used
- Node.js
- PostgreSQL (RDS)
- AWS EC2
- AWS Application Load Balancer

## Deployment
The SignMeUp service is deployed on AWS EC2, utilizing RDS PostgreSQL for the database. An AWS Application Load Balancer is implemented for efficient traffic distribution.

## Contact
omkarshirote@gmail.com or +91827556152
