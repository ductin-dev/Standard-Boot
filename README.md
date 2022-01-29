# Spring Boot Single Service
You can check the full article at [RESTful Microservices with Spring Boot and Kubernetes] www.satdevelop.com

##Overview
This repo consists of following artifacts
- OpenApi spec for product catalog service.
- API implementation `ProductCatalogController` 
- Spring Data JPA implemenation of repositories.
- A basic error handling.

### Package Structure

- **resource**: API implementation
- **application**: core business logic
- **persistence**: spring data JPA implemenation of repository classes
- **common**: error handling and spring bean configuration
